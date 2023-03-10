# HTML INPUT TYPES

This chapter describes the different types for the HTML `<input>` element.

`<input type="text">` defines a single-line text input field.

`<input type="password">` defines a password field.

`<input type="submit">` defines a button for submitting form data to a form-handler.

`<input type="reset">` defines a reset button.

`<input type="radio">` defines a radio button.

`<input type="checkbox">` defines a checkbox.

`<input type="button">` defines a button.

The `<input type="color">` is used for input fields that should contain a color.

The `<input type="date">` is used for input fields that should contain a date.

the `min` and `max` attributes to add restrictions to dates.

The `<input type="datetime-local">` specifies a date and time input field, with no time zone.

The `<input type="email">` is used for input fields that should contain an e-mail address.

The `<input type="image">` defines an image as a submit button.

The `<input type="file">` defines a file-select field.

The `<input type="hidden">` defines a hidden input field (not visible to a user).

The `<input type="month">` allows the user to select a month and year.

The `<input type="number">` defines a numeric input field.

The `<input type="range">` defines a control. what numbers are accepted with the `min`, `max`, and `step` attributes.

The `<input type="search">` is used for search fields.

The `<input type="tel">` is used for input fields that should contain a telephone number.

The `<input type="time">` allows the user to select a time.

The `<input type="url">` is used for input fields.

The `<input type="week">` allows the user to select a week and year.

```html

<label for="fname">First name:</label><br>
<input type="text" id="fname" name="fname" />

<label for="pwd">Password:</label><br>
<input type="password" id="pwd" name="pwd" />

<input type="submit" value="Submit">

<input type="reset" />

<form>
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label>
</form>

<form>
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a bike</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a car</label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
  <label for="vehicle3"> I have a boat</label>
</form>

<form>
  <label for="favcolor">Select your favorite color:</label>
  <input type="color" id="favcolor" name="favcolor">
</form>

<form>
  <label for="birthday">Birthday:</label>
  <input type="date" id="birthday" name="birthday">
</form>

<form>
  <label for="datemax">Enter a date before 1980-01-01:</label>
  <input type="date" id="datemax" name="datemax" max="1979-12-31"><br><br>
  <label for="datemin">Enter a date after 2000-01-01:</label>
  <input type="date" id="datemin" name="datemin" min="2000-01-02">
</form>

<form>
  <label for="birthdaytime">Birthday (date and time):</label>
  <input type="datetime-local" id="birthdaytime" name="birthdaytime">
</form>

<form>
  <label for="email">Enter your email:</label>
  <input type="email" id="email" name="email">
</form>

<form>
<input type="image" src="img_submit.gif" alt="Submit" width="48" height="48">
</form>

<form>
  <label for="myfile">Select a file:</label>
  <input type="file" id="myfile" name="myfile">
</form>

<form>
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <input type="hidden" id="custId" name="custId" value="3487">
  <input type="submit" value="Submit">
</form>

<form>
  <label for="bdaymonth">Birthday (month and year):</label>
  <input type="month" id="bdaymonth" name="bdaymonth">
</form>

<form>
  <label for="quantity">Quantity (between 1 and 5):</label>
  <input type="number" id="quantity" name="quantity" min="1" max="5">
</form>

<form>
  <label for="vol">Volume (between 0 and 50):</label>
  <input type="range" id="vol" name="vol" min="0" max="50">
</form>

<form>
  <label for="gsearch">Search Google:</label>
  <input type="search" id="gsearch" name="gsearch">
</form>

<form>
  <label for="phone">Enter your phone number:</label>
  <input type="tel" id="phone" name="phone" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}">
</form>

<form>
  <label for="appt">Select a time:</label>
  <input type="time" id="appt" name="appt">
</form>

<form>
  <label for="homepage">Add your homepage:</label>
  <input type="url" id="homepage" name="homepage">
</form>

<form>
  <label for="week">Select a week:</label>
  <input type="week" id="week" name="week">
</form>

```
