# HTML Computer Code

The HTML `<kbd>` element is used to define keyboard input.

The HTML `<samp>` element is used to define sample output from a computer program.

The HTML `<code>` element  is used to define a piece of computer code.

The `<var>` element defines a variable in programming or in a mathematical expression.

fix this, you can put the `<code>` element inside a `<pre>` element:

```html

<!DOCTYPE html>
<html>
<body>

<p>Save the document by <kbd>pressing</kbd> Ctrl + S</p>

<p>File not found.<samp>Press F1 to continue</samp></p>

<code>
x = 5;
y = 6;
z = x + y;
</code>

<p>The area of a <var>triangle</var> is: 1/2 x b x <var>h</var>, where <var>b</var> is the base, and <var>h</var> is the vertical height.</p>

<pre>
<code>
x = 5;
y = 6;
z = x + y;
</code>
</pre>

</body>
</html>

```
