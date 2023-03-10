# HTML Style Guide

we strongly recommend to always add the `<html>` and `<body>` tags.

we recommend using the `<head>` tag.

include the following `<meta>` element in all your web pages.

HTML allows mixing uppercase and lowercase letters in attribute names.

Lowercase is easier to write.we strongly recommend closing all HTML elements, like this.

the `alt` attribute for images. This attribute is important if the image for some reason cannot be displayed.

the `width` and `height` of images. This reduces flickering, because the browser can reserve space for the image before loading.

comments should be written on `one line Commentss`, like this.

Comments that spans `one or more line Comments`, should be written like this.

Using "untidy" HTML code can result in JavaScript.

```html

<!DOCTYPE html>
<html>
<head>
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- This is a comment -->

    <img src="html5.gif" alt="HTML5" style="width:128px;height:128px">

    <p>This is a paragraph.</p>

    <a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a>

    <!--
        This is a long comment example. This is a long comment example.
        This is a long comment example. This is a long comment example.
    -->

    <section>
        <p>This is a paragraph.</p>
        <p>This is a paragraph.</p>

        <table class="striped">This is table</table>

    </section>

    <p id="demo">This is paragraph 2.</p>

    <script>
        document.getElementById("demo").innerHTML = "HELLO.";
    </script>

</body>
<html>
```
