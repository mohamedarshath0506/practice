# Title

Links

## Description

HTML Links - Syntax a> tag defines a hyperlink. HTML Links - The target Attribute, Both examples above are using an absolute URL (a full web address) in the href attribu.To use an image as a link, just put the img tag inside the a tag, inside the href attribute to create a link that opens the user's email program.To use an HTML button as a link, you have to add some JavaScript code.The title attribute specifies extra information about an element.

```md040

<!DOCTYPE html>
<html>
<body>

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

</body>
</html>


```
