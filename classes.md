# HTML Classes

three `<div>` elements with a class attribute with the value of "city". All of the three `<div>` elements will be styled equally according to the .city style.

syntax for `class` is: write a hash character (.), followed by an class name. Then, define the CSS properties within curly braces {}.

JavaScript can access elements with a specific class name with the `getElementsByClassName()` method.

```html
<!DOCTYPE html>
<html>
<head>
<style>
.city {
  background-color: tomato;
  color: white;
  border: 2px solid black;
  margin: 20px;
  padding: 20px;
}
</style>
</head>
<body>

<div class="city">
<h2>London</h2>
<p>London is the capital of England.</p>
</div> 

<div class="city">
<h2>Paris</h2>
<p>Paris is the capital of France.</p>
</div>

<div class="city">
<h2>Tokyo</h2>
<p>Tokyo is the capital of Japan.</p>
</div>

<button onclick="myFunction()">Hide elements</button>
+
<script>
function myFunction() {
  var x = document.getElementsByClassName("city");
  for (var i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
}
</script>

</body>
</html>

```
