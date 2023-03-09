# HTML Links

attribute of the `<a>` element is the `href` attribute, which indicates the link's destination.

The `target` attribute can have one of the following values.

To use an image as a link, just put the `<img>` tag inside

such as a click of a button.

A link can also be styled as a button, by using CSS.

```html

<a href="url">link text</a>
<a href="https://www.w3schools.com/">Visit W3Schools.com!</a>
<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>

<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>

<a href="default.asp"><img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;"></a>

<a href="mailto:someone@example.com">Send email</a>

<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>

<button onclick="document.location='default.asp'">HTML Tutorial</button>

```

```css
<!DOCTYPE html>
<html>
<head>
<style>
a:link, a:visited {
  background-color: #f44336;
  color: white;
  padding: 15px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}

a:hover, a:active {
  background-color: red;
}
</style>
</head>
<body>

<h2>Link Button</h2>
<p>A link styled as a button:</p>
<a href="default.asp" target="_blank">This is a link</a>

</body>
</html>

```