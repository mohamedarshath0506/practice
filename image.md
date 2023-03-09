# HTML Image

Use the HTML `<img>` element to define an image.

Use the HTML `src` attribute to define the URL of the image.

Use the HTML `alt` attribute to define an alternate text for an image, if it cannot be displayed

Use the HTML `width` and `height` attributes or the CSS `width` and `height` properties to define the size of the image.

To add a background image on an HTML element, use the HTML `style` attribute and the CSS `background-image` property.

the background image in the `<style>` element, in the `<head>` section.

the background image from repeating itself, set the `background-repeat` property to `no-repeat`.

he background image to cover the entire element, you can set the `background-size` property to `cover`.

to make sure the entire element is always covered, set the `background-attachment` property to `fixed`.

the `<picture>` element.Use the first `<source>` element with matching attribute values.`<img>` element to define an image.`src` attribute to define the URL of the image.the HTML `style` attribute

```html
<!DOCTYPE html>
<html>
<head>

<style>

body {
  background-image: url('img_girl.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
}

p {
  background-image: url('img_girl.jpg');
}
</style>

</head>

<body>
<img src="img_chania.jpg" alt="Flowers in Chania" width="460" height="345">

<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">

<img src="html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">

<img src="https://www.w3schools.com/images/w3schools_green.jpg" alt="W3Schools.com">

<a href="default.asp">

<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">

</a>

<p background-image: url('img_girl.jpg');>
You can specify background images<br>
for any visible HTML element.<br>
In this example, the background image<br>
is specified for a p element.<br>
By default, the background-image<br>
will repeat itself in the direction(s)<br>
where it is smaller than the element<br>
where it is specified. (Try resizing the<br>
browser window to see how the<br>
background image behaves.
</p>

<style>

img {
  width: 100%;
}

body {
  background-image: url('img_girl.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed; 
  background-size: 100% 100%;
}

</style>
</body>
</html>
```

```html

<picture>
  <source srcset="img_avatar.png">
  <source srcset="img_girl.jpg">
  <img src="img_beatles.gif" alt="Beatles" style="width:auto;">
</picture>
```
