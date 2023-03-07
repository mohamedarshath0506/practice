# Title

CSS

## Description

Inline - by using the style attribute inside HTML elements
Internal - by using a style element in the head section
External - by using a link element to link to an external CSS file.

```md040
attribute
<!DOCTYPE html>
<html>
<body>
<h1 style="color:blue;">A Blue Heading</h1>
<p style="color:red;">A red paragraph.</p>
</body>
</html>
style element in the head
<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>
<h1>This is a heading</h1>
<p>This is a paragraph.</p>
</body>
</html>
link element to link to an external CSS
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<h1>This is a heading</h1>
<p>This is a paragraph.</p>
</body>
</html>
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}
```
