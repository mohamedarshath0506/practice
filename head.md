# HTML Head

The HTML `<head>` element is a container for the following elements. `<title>`, `<style>`, `<meta>`, `<link>`, `<script>`, and `<base>`.

The `<head>` element is a container for metadata (data about data).

The `<style>` element is used to define style information for a single HTML page.

The `<link>` tag is most often used to link to external style sheets.

The `<meta>` element is typically used to specify the character set, page description, keywords, author of the document.

The `<script>` element is used to define client-side JavaScripts.

The `<title>` element is required in HTML documents.

The `<base>` element specifies the base URL and/or target for all relative URLs in a page.

```html
<!DOCTYPE html>
<html>
<head>
 
 <title>Page Title</title>
 
 <meta name="description" content="Free Web tutorials">
 
 <link rel="stylesheet" href="mystyle.css">
 
 <style>
    body {background-color: powderblue;}
    h1 {color: red;}
    p {color: blue;}
  </style>

 <base href="https://www.w3schools.com/" target="_blank">

  <script>
  function myFunction() {
    document.getElementById("demo").innerHTML = "Hello JavaScript!";
  }
  </script>

</head>
<body>

</body>
</html>

```
