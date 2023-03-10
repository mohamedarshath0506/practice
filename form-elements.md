# HTML Form Elements

The HTML `<form>` element can contain one or more of the following form elements:

The `<input>` element can be displayed in several ways, depending on the type attribute.

The `<select>` element defines a drop-down list.

The `<option>` elements defines an option that can be selected.

To define a pre-selected option, add the `selected` attribute to the option:

the `size` attribute to specify the number of visible values.

the `multiple` attribute to allow the user to select more than one value.

The `<textarea>` element defines a multi-line input field (a text area).

The `rows` attribute specifies the visible number of lines in a text area.

The `cols` attribute specifies the visible width of a text area.

The `<button>` element defines a clickable button.

The `<fieldset>` element is used to group related data in a form.

The `<legend>` element defines a caption for the `<fieldset>` element.

The `<datalist>` element specifies a list of pre-defined options for an `<input>` element.

The list attribute of the `<input>` element, must refer to the id attribute of the `<datalist>` element.

```html

<label for="fname">First name:</label>
<input type="text" id="fname" name="fname">

<label for="cars">Choose a car:</label>
<select id="cars" name="cars">
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
    <option value="fiat">Fiat</option>
    <option value="audi">Audi</option>
</select>

<option value="fiat" selected>Fiat</option>

<label for="cars">Choose a car:</label>
<select id="cars" name="cars" size="3">
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
</select>

<label for="cars">Choose a car:</label>
<select id="cars" name="cars" size="4" multiple>
    <option value="fiat">Fiat</option>
    <option value="audi">Audi</option>
</select>

<textarea name="message" rows="10" cols="30">
    The cat was playing in the garden.
</textarea>

<button type="button" onclick="alert('Hello World!')">Click Me!</button>

<form action="/action_page.php">
  <fieldset>
    <legend>Personalia:</legend>
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname" value="John"><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname" value="Doe"><br><br>
    <input type="submit" value="Submit">
  </fieldset>
</form>

<form action="/action_page.php">
  <input list="browsers">
  <datalist id="browsers">
    <option value="Internet Explorer">
    <option value="Firefox">
    <option value="Chrome">
    <option value="Opera">
    <option value="Safari">
  </datalist>
</form>

```
