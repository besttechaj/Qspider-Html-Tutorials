CSS Selector

CSS selectors are used to select the content you want to style. CSS selectors select HTML elements according to its id, class, type, attribute etc.

There are several different types of selectors in CSS.

a) CSS Element Selector
b) CSS Id Selector
c) CSS Class Selector
d) CSS Universal Selector
e) CSS Group Selector

1. CSS Element Selector
   The element selector selects the specified HTML element by name.

   To access one element selector

<!-- <!DOCTYPE html>
<html>
<head>
<style>
p{
    text-align: center;
    color: blue;
}
</style>
</head>
<body>
<p>This style will be applied on every paragraph.</p>
<p id="para1">Me too!</p>
<p>And me!</p>
</body>
</html> -->

2. CSS Id Selector :
   It should be always unique

   The id selector selects the id attribute of an HTML element to select a specific element. An id is always unique within the page so it is chosen to select a single, unique element.

It is written with the hash character (#), followed by the id of the element.

<!-- <!DOCTYPE html>
<html>
<head>
<style>
# para1 {
    text-align: center;
    color: blue;
}
</style>
</head>
<body>
<p id="para1">Hello Javatpoint.com</p>
<p>This paragraph will not be affected.</p>
</body>
</html> -->

3. CSS Class Selector
   The class selector selects HTML elements with a specific class attribute. It is used with a period character . (full stop symbol) followed by the class name.

Note: A class name should not be started with a number.
Let's take an example with a class "center".

<!-- <!DOCTYPE html>
<html>
<head>
<style>
.center {
    text-align: center;
    color: blue;
}
</style>
</head>
<body>
<h1 class="center">This heading is blue and center-aligned.</h1>
<p class="center">This paragraph is blue and center-aligned.</p>
</body>
</html>   -->

CSS Class Selector for specific element :

If you want to specify that only one specific HTML element should be affected then you should use the element name with class selector.

Let's see an example.

<!-- <!DOCTYPE html>
<html>
<head>
<style>
p.center {
    text-align: center;
    color: blue;
}
</style>
</head>
<body>
<h1 class="center">This heading is not affected</h1>
<p class="center">This paragraph is blue and center-aligned.</p>
</body>
</html> -->

NOtes from q-spider :
-We can provide multiple class name for single element
-We can provide common class name for different element
-In Css, first we have to mention (.) followed by the className to access className
-class name should start with alphabets only
-we can use numbers but we cannot start with numbers while writing class name

4. CSS Universal Selector / CSS Global Selector :
   The universal selector is used as a wildcard character. It selects all the elements on the pages.
   To change every element at same time
   No need to provide class, id, tagName

<!-- <!DOCTYPE html>
<html>
<head>
<style>
* {
   color: green;
   font-size: 20px;
}
</style>
</head>
<body>
<h2>This is heading</h2>
<p>This style will be applied on every paragraph.</p>
<p id="para1">Me too!</p>
<p>And me!</p>
</body>
</html> -->

5. CSS Group Selector
   The grouping selector is used to select all the elements with the same style definitions.

Grouping selector is used to minimize the code. Commas are used to separate each selector in grouping.

Let's see the CSS code without group selector.

<!-- h1 {
 text-align: center;
 color: blue;
}
h2 {
 text-align: center;
 color: blue;
}
p {
 text-align: center;
 color: blue;
}
As you can see, you need to define CSS properties for all the elements. It can be grouped in following ways:

h1,h2,p {
 text-align: center;
 color: blue;
}   -->

Let's see the full example of CSS group selector.

<!-- <!DOCTYPE html>
<html>
<head>
<style>
h1, h2, p {
    text-align: center;
    color: blue;
}
</style>
</head>
<body>
<h1>Hello Javatpoint.com</h1>
<h2>Hello Javatpoint.com (In smaller font)</h2>
<p>This is a paragraph.</p>
</body>
</html>   -->

**\*\*\*\***\***\*\*\*\*** IMPORTANT POINT FOR INTERVIEW

SELECTOR TYPES ----> ID, CLASS, ELEMENT, GROUPING, UNIVERSAL OR GLOBAL SELECTOR

IF WE APPLY ALL TYPES OF SELECTOR PROPERTY TO A SPECIFIC ELEMENT THEN WHAT WILL BE THE PRIORITY FOR SELECTORS?
1ST PREFERENCE IS ALWAYS GIVEN TO "ID" SINCE IT IS UNIQUE
2ND PREFERENCE IS GIVEN TO CLASS
3RD PREFERENCE DEPENDS WHICH PROPERTY IS MENTION LAST GROUPING OR ELEMENT
4RD PREFERENCE DEPENDS WHICH PROPERTY IS MENTION LAST GROUPING OR ELEMENT
LAST PREFERENCE IS ALWAYS GIVEN TO UNIVERSAL/GLOBAL SELECTOR
