# HTML Table

Set the background color of the three columns with the `<colgroup>` and `<col>` tags.

Each table row starts with a `<tr>` and ends with a `</tr>` tag. the text in `<th>` elements are bold and centered, but you can change that with CSS.

Table header cells. In those cases use the `<th>` tag instead of the `<td>` tag.

Table cell is defined by a `<td>` and a `</td>` tag.

An HTML table with a `<thead>`, `<tbody>`, and a `<tfoot>` element.

set the size of a specific column, add the `style` attribute on a `<th>` or `<td>` element.

the height of a specific row, add the `style` attribute on a table row element.

make a cell span over multiple columns, use the `colspan` attribute.

make a cell span over multiple rows, use the `rowspan` attribute:

others sides with the `padding-top` `padding-bottom`, `padding-left`, and `padding-right` properties.

table cells, use the CSS `border-spacing` property on the `table` element.

To style every other table row element, use the `:nth-child(even)` selector.

The `<colgroup>` element should be used as a container for the column specifications.

Each group is specified with a `<col>` element.

The `span` attribute specifies how many columns that get the style.

The `style` attribute specifies the style to give the columns.

```html
<!DOCTYPE html>
<html>
<style>
table, th, td {
  border:1px solid black;
}

th, td {
  padding-top: 10px;
  padding-bottom: 20px;
  padding-left: 30px;
  padding-right: 40px;
}

table {
  border-spacing: 30px;
}

tr:nth-child(even) {
  background-color: #D6EEEE;
}

</style>
<body>

<h2>TH elements define table headers</h2>

<table style="width:100%">

<caption>Monthly savings</caption>

<colgroup>
    <col span="2" style="background-color:red">
    <col style="background-color:yellow">
  </colgroup>

  <tr style="width:70%">
    <th colspan="2">Person 1</th>
    <th>Person 2</th>
    <th>Person 3</th>
  </tr>
  <tr style="height:200px">
    <td rowspan="2">Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
  <tr>
    <td>16</td>
    <td>14</td>
    <td>10</td>
  </tr>
</table>

<table>
  <thead>
    <tr>
      <th>Month</th>
      <th>Savings</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>January</td>
      <td>$100</td>
    </tr>
    <tr>
      <td>February</td>
      <td>$80</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>Sum</td>
      <td>$180</td>
    </tr>
  </tfoot>
</table>

<p>To understand the example better, we have added borders to the table.</p>

</body>
</html>

```
