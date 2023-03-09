# HTML Id

The `id` attribute specifies a unique id for an HTML element. The value of the id attribute must be unique within the HTML.

syntax for id is: write a hash character (#), followed by an id name. Then, define the CSS properties within curly braces {}.

JavaScript can access an element with a specific id with the getElementById() method.

```html
<!DOCTYPE html>
<html>
<body>

<h2>Using The id Attribute in JavaScript</h2>
<p>JavaScript can access an element with a specified id by using the getElementById() method:</p>

<h1 id="myHeader">Hello World!</h1>
<button onclick="displayResult()">Change text</button>

<script>
function displayResult() {
  document.getElementById("myHeader").innerHTML = "Have a nice day!";
}
</script>

</body>
</html>

```
