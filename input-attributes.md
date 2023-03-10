# HTML Input Attributes

the different attributes for the HTML `<input>` element.

The input `value` attribute specifies an initial value for an input field.

The input `readonly` attribute specifies that an input field is read-only.

The input `disabled` attribute specifies that an input field should be disabled.

The input `size` attribute specifies the visible width, in characters, of an input field.

The input `maxlength` attribute specifies the maximum number of characters allowed in an input field.

The input `min` and `max` attributes specify the minimum and maximum values for an input field.

The `multiple` attribute works with the following input types: email, and file.

The `pattern` attribute works with the following input types: text, date, search, url, tel, email, and password.

The input `placeholder` attribute specifies a short hint that describes the expected value of an input field.

The input `required` attribute specifies that an input field must be filled out before submitting the form.

The input `step` attribute specifies the legal number intervals for an input field.

The input `autofocus` attribute specifies that an input field should automatically get focus when the page loads.

The input `height` and `width` attributes specify the height and width of an `<input type="image">` element.

The input `list` attribute refers to a `<datalist>` element that contains pre-defined options for an `<input>` element.

The `autocomplete` attribute works with `<form>` and the following `<input>` types: text, search, url, tel, email, password, datepickers, range, and color.

```html
<label for="fname">First name:</label><br>
<input type="text" id="fname" name="fname" value="John">

<label for="fname">First name:</label><br>
<input type="text" id="fname" name="fname" value="John" readonly>

<label for="fname">First name:</label><br>
<input type="text" id="fname" name="fname" value="John" disabled>

<label for="fname">First name:</label><br>
<input type="text" id="fname" name="fname" size="50">

<label for="pin">PIN:</label><br>
<input type="text" id="pin" name="pin" maxlength="4" size="4">

<form>
    <label for="datemax">Enter a date before 1980-01-01:</label>
    <input type="date" id="datemax" name="datemax" max="1979-12-31"><br><br>

    <label for="datemin">Enter a date after 2000-01-01:</label>
    <input type="date" id="datemin" name="datemin" min="2000-01-02"><br><br>
</form>

  <label for="files">Select files:</label>
  <input type="file" id="files" name="files" multiple>

<label for="country_code">Country code:</label>
  <input type="text" id="country_code" name="country_code"
  pattern="[A-Za-z]{3}" title="Three letter country code">

<label for="phone">Enter a phone number:</label>
  <input type="tel" id="phone" name="phone"
  placeholder="123-45-678"
  pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}">

<label for="username">Username:</label>
    <input type="text" id="username" name="username" required>

<label for="points">Points:</label>
  <input type="number" id="points" name="points" step="3">

<label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" autofocus>

<input type="image" src="img_submit.gif" alt="Submit" width="48" height="48">

<input list="browsers">
  <datalist id="browsers">
    <option value="Internet Explorer">
  </datalist>

<form action="/action_page.php" autocomplete="on">
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" autocomplete="off"><br><br>
  <input type="submit" value="Submit">
</form>

```
