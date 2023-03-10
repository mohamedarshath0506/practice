# HTML Responsive

To create a responsive website, add the following `<meta>` tag to all your web pages.

the CSS `width` property is set to 100%, the image will be responsive and scale up and down.the `max-width` property is set to 100%, the image will scale down if it has to, but never scale up to be larger than its original size.HTML `<picture>` element allows you to define different images for different browser window sizes.

That way the text size will follow the size of the browser window.

CSS is a modern CSS framework with support for desktop, tablet, and mobile design by default.

CSS is smaller and faster than similar CSS frameworks.

CSS is designed to be independent of jQuery or any other JavaScript library.

```html
<!DOCTYPE html>
<html>
<head>
<title>W3.CSS</title>

<meta name="viewport" content="width=device-width, initial-scale=1">

<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>

</head>
<body>

<picture>
  <source srcset="img_smallflower.jpg" media="(max-width: 600px)">
  <source srcset="img_flowers.jpg" media="(max-width: 1500px)">
  <source srcset="flowers.jpg">
  <img src="img_smallflower.jpg" alt="Flowers">
</picture>

<div class="w3-container w3-green">
  <h1>W3Schools Demo</h1> 
  <p>Resize this responsive page!</p> 
</div>


</body>
</html>


```
