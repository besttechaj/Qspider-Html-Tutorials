CSS PROPERTY

The border property is a shorthand property for:

tag_Name {
border: border-width border-style border-color;
}

border-width / thickness
border-style type (required) eg solid, dotted
border-color
If border-color is omitted, the color applied will be the color of the text.

h1 {
border: 5px solid red;
}

> > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > >

CSS border-collapse Property

Definition and Usage
The border-collapse property sets whether table borders should collapse into a single border or be separated as in standard HTML.

CSS Syntax
border-collapse: separate|collapse|initial|inherit;

Property Values
Value Description
separate : Borders are separated; each cell will display its own borders. This is default.
collapse : Borders are collapsed into a single border when possible (border-spacing and empty-cells properties have no effect)
initial : Sets this property to its default value. Read about initial
inherit : Inherits this property from its parent element. Read about inherit

> > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > >

HTML | <th> colspan Attribute
Read
Discuss
Courses
The <th> colspan Attribute in HTML is used to specify a number of columns a header cell should span.

Syntax:

<th colspan="number">
Attribute Values: It contains single value number which contains the numeric value to sets the number of column a header cell should span.

Example: This example illustrates the use of colspan attribute in <th> tag.

<!--
<!DOCTYPE html>
<html>
    <head>
        <title>HTML colspan Attribute</title>
        <style>
            table, th, td {
                border: 1px solid black;
                border-collapse: collapse;
                padding: 6px;
            }
        </style>
    </head>

    <body>

        <h1 style = "color: green;">GeeksforGeeks</h1>
        <h2>HTML &lt;th&gt;colspan Attribute</h2>

        <table>
            <tr>
                <th colspan="2">Expense</th>
            </tr>

            <tr>
                <td>Arun</td>
                <td>$10</td>
            </tr>

            <tr>
                <td>Priya</td>
                <td>$8</td>
            </tr>
        </table>
    </body> -->

> > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > > >

HTML <td> colspan Attribute

Example
An HTML table with a table cell that spans two columns:

<!-- <table>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$80</td>
  </tr>
  <tr>
    <td colspan="2">Sum: $180</td>
  </tr>
</table> -->

Definition and Usage
The colspan attribute defines the number of columns a cell should span.

<td colspan="number">
Attribute Values
Value                  Description
number                 Specifies the number of columns a cell should span
