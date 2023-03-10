# HTML Form Attributes

he different attributes for the HTML `<form>` element.

The `action` attribute defines the action to be performed when the form is submitted.

The `target` attribute can have one of the following values.

The `method` attribute specifies the HTTP method to be used when submitting the form data.

The form-data can be sent as URL variables (with `method="get"`) or as HTTP post transaction (with `method="post"`).

The `autocomplete` attribute specifies

The `novalidate` attribute is a boolean attribute.

```html

<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>

<form action="/action_page.php" target="_blank">

<form action="/action_page.php" method="get">

<form action="/action_page.php" method="post">

<form action="/action_page.php" autocomplete="on">

<form action="/action_page.php" novalidate>
```
