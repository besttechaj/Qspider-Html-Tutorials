HTML Lists

HTML Lists are used to specify lists of information. All lists may contain one or more list elements. There are three different types of HTML lists:

Ordered List or Numbered List (ol)
Unordered List or Bulleted List (ul)
Description List or Definition List (dl)
Note: We can create a list inside another list, which will be termed as nested List.
HTML Ordered List or Numbered List
In the ordered HTML lists, all the list items are marked with numbers by default. It is known as numbered list also. The ordered list starts with <ol> tag and the list items start with <li> tag.

<!-- <ol>
 <li>Aries</li>
 <li>Bingo</li>
 <li>Leo</li>
 <li>Oracle</li>
</ol>   -->

HTML Unordered List or Bulleted List
In HTML Unordered list, all the list items are marked with bullets. It is also known as bulleted list also. The Unordered list starts with <ul> tag and list items start with the <li> tag.

<!-- <ul>
 <li>Aries</li>
 <li>Bingo</li>
 <li>Leo</li>
 <li>Oracle</li>
</ul>   -->

HTML Description List or Definition List
HTML Description list is also a list style which is supported by HTML and XHTML. It is also known as definition list where entries are listed like a dictionary or encyclopedia.

The definition list is very appropriate when you want to present glossary, list of terms or other name-value list.

The HTML definition list contains following three tags:

<!-- <dl> tag defines the start of the list.
<dt> tag defines a term.
<dd> tag defines the term definition (description).
<dl>
  <dt>Aries</dt>
  <dd>-One of the 12 horoscope sign.</dd>
  <dt>Bingo</dt>
  <dd>-One of my evening snacks</dd>
 <dt>Leo</dt>
 <dd>-It is also an one of the 12 horoscope sign.</dd>
  <dt>Oracle</dt>
  <dd>-It is a multinational technology corporation.</dd>
</dl> -->

HTML Nested List
A list within another list is termed as nested list. If you want a bullet list inside a numbered list then such type of list will called as nested list.

Code:

<!-- <!DOCTYPE html>
<html>
<head>
    <title>Nested list</title>
</head>
<body>
    <p>List of Indian States with thier capital</p>
<ol>
    <li>Delhi
        <ul>
            <li>NewDelhi</li>
        </ul>
    </li>
    <li>Haryana
        <ul>
            <li>Chandigarh</li>
        </ul>
    </li>
    <li>Gujarat
        <ul>
            <li>Gandhinagar</li>
        </ul>
    </li>
    <li>Rajasthan
        <ul>
            <li>Jaipur</li>
        </ul>
    </li>
    <li>Maharashtra
        <ul>
            <li>Mumbai</li>
        </ul>
    </li>
    <li>Uttarpradesh
        <ul>
            <li>Lucknow</li></ul>
    </li>
</ol>
</body>
</html> -->
