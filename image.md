# Title

Image

## Description

The src attribute specifies the path (URL) to the image.You can use the style attribute to specify the width and height of an image.The width, height, and style attributes are all valid in HTML.Some web sites point to an image on another server.To use an image as a link, put the img tag inside the a tag.To add a background image on an HTML element, use the HTML style attribute and the CSS background-image.the browser window, and you will see that the image will stretch, but always cover the entire element.

```md040
<!DOCTYPE html>
<html>
<head>

</head>
<body>
<img src="img_chania.jpg" alt="Flowers in Chania" width="460" height="345">
<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">
<img src="html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">
<img src="https://www.w3schools.com/images/w3schools_green.jpg" alt="W3Schools.com">
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
<p>
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
p {
  background-image: url('img_girl.jpg');
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
