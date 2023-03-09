# HTML List

unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.

ordered list starts with the `<ol>` tag. Each list item starts with the `<li>` tag.

The `<dl>` tag defines the description list, the `<dt>` tag defines the term (name), and the `<dd>` tag describes each term.

the HTML `<ul>` element to define an unordered list.the HTML `<li>` element to define a list item.Lists can be `nested`.

the HTML `<ol>` element to define an ordered list.Use the HTML `<li>` element to define a list item.Lists can be `nested`.

```html
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>

<ul>
  <li>Coffee</li>
  <li>Tea
    <ul>
      <li>Black tea</li>
      <li>Green tea</li>
    </ul>
  </li>
  <li>Milk</li>
</ul>

<ol>
  <li>Coffee</li>
  <li>Tea
    <ol>
      <li>Black tea</li>
      <li>Green tea</li>
    </ol>
  </li>
  <li>Milk</li>
</ol>

```
