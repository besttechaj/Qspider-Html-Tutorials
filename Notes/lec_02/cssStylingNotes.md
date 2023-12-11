tags are of two types : closing tag and empty tag

closing tag : Some HTML elements have content which is written between opening tag and closing tag.
eg

<div></div>
<h1>heading tag</h1>

Empty tag:
Note: Some HTML elements have no content (like the <br>, <img>, <hr> element). These elements are called empty elements. Empty elements do not have an end tag!

CSS ( CASCADING STYLE SHEET ):

It is a styling language and used to design web pages

Types of CSS (Cascading Style Sheet)

Cascading Style Sheet (CSS) is used to set the style in web pages that contain HTML elements. It sets the background color, font-size, font-family, color, … etc. properties of elements on a web page.

There are three types of CSS which are given below:

a) Inline CSS
b) Internal or Embedded CSS
c) External CSS

INLINE CSS :

example

<!--
<!DOCTYPE html>
<html>
<head>
    <title>Inline CSS</title>
</head>

<body>
    <p style="color:#009900; font-size:50px;
             font-style:italic; text-align:center;">
        GeeksForGeeks
    </p>
</body>
</html> -->

Internal or Embedded CSS

- Internal styling is also known as Embedded styling
- we provide styling inside the <style> tag in the header section ie <head> tag

example

<!-- <!DOCTYPE html>
<html>
<head>
    <title>Internal CSS</title>
    <style>
        .main {
            text-align: center;
        }

        .GFG {
            color: #009900;
            font-size: 50px;
            font-weight: bold;
        }

        .geeks {
            font-style: bold;
            font-size: 20px;
        }
    </style>
</head>

<body>
    <div class="main">
        <div class="GFG">GeeksForGeeks</div>

        <div class="geeks">
            A computer science portal for geeks
        </div>
    </div>
</body>
</html> -->

EXTERNAL CSS

- Here we need to link our css file with the html file

example

<!--
<!DOCTYPE html>
<html>
<head>

    <link rel="stylesheet" href="geeks.css" />
>>>>>>>>>>>>
rel means relative

rel = "stylesheet" means this link is relative to stylesheet

href means hyperText-Reference
href = "file_path or file_location"

</head>

<body>
    <div class="main">
        <div class="GFG">GeeksForGeeks</div>
        <div id="geeks">
            A computer science portal for geeks
        </div>
    </div>
</body>
</html>

body {
    background-color:powderblue;
}
.main {
    text-align:center;
}
.GFG {
    color:#009900;
    font-size:50px;
    font-weight:bold;
}
#geeks {
    font-style:bold;
    font-size:20px;
} -->

IMPORTANT QUESTION **\*\***\*\***\*\***\*\***\*\***\*\***\*\***

If we provide inline css, internal css, external css to the same element . Which has higher priority??

ans --> 1st preference will be given to inline css
2nd preference ---> Depends on the last css specified value. it can be internal css or external css depending on the which css styling had been preferred last.
