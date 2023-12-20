Explain the positions property in CSS

In this article, we will see what is position property, and how to use this property wisely in order to make web pages. The CSS position property is used to align the different elements in the HTML page. CSS position property plays an important role to make high-quality web pages. The CSS position property is used to define the position of the element on the web page. By using the top, left, bottom, right, and z-index, we can identify the exact position of the element.

There are 5 position properties in CSS:

static (default)
relative
absolute
fixed
sticky
Syntax:

selector{
position: value;
}
value = static, relative, absolute, fixed, sticky
Let’s understand each of these properties one by one.

Note: The positioned element means an element having a position property other than static.

position: static It is the default position value for the element. Under static position, elements are positioned according to the normal flow of the page.

Note: left, right, top, and bottom properties will not affect if the position is static.

Example: In this example, we will use static css position property.

<!--
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        .purple {
            height: 200px;
            width: 200px;
            color: black;
            font-size: 1.5rem;
            padding: 10px;
            background-color: purple;
        }
        .cyan {
            position: static;
            font-size: 1.5rem;
            padding: 10px;
            height: 200px;
            width: 200px;
            background-color: cyan;
        }
    </style>
</head>
<body>
    <div class="purple">
        I am reference
    </div>
    <div class="cyan">
        I am static element
    </div>
</body>
</html> -->

Output:

Position: Relative In this case, the element remains in the normal flow of the document but left, right, top, and bottom affects. Elements get shifted from their original position in the document creating vacant space and other elements may adjust themselves according to the vacant space left by the element.

Example: In this example, we will use the relative css position property.

<!--
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        .purple {
            height: 200px;
            width: 200px;
            color: black;
            font-size: 1.5rem;
            padding: 10px;
            background-color: purple;
        }
        .cyan {
            position: relative;
            left: 100px;
            top: 90px;
            font-size: 1.5rem;
            padding: 10px;
            height: 200px;
            width: 200px;
            background-color: cyan;
        }
    </style>
</head>
<body>
    <div class="purple"> I am reference </div>
    <div class="cyan"> I am relative element </div>
</body>
</html> -->

Output:

Explanation: We can see here element change its left and top from the original position creating some space.

position: Absolute elements do not follow the normal flow document instead they position themselves relative to the closest positioned ancestor. Its final position is determined using the top, bottom, left and right.

Note: The positioned element means an element having a position property other than static.

These element does not occupy any space and other elements treats absolute elements like there is no element. Parent element should be positioned and position property other than absolute and If parent element is not positioned then absolute element position themselves according to nearest positioned ancestor. We generally set z-index when using absolute position.

Consider Two cases to understand absolute position:

1st case: When the parent property value is positioned means the position property of the parent is not equal to static.

<!--
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        .purple {
            position: relative;
            height: 200px;
            width: 200px;
            color: black;
            font-size: 1.5rem;
            padding: 10px;
            background-color: purple;
        }
        .cyan {
            position: absolute;
            bottom: 10px;
            left: 70px;
            font-size: 1.5rem;
            padding: 10px;
            height: 100px;
            width: 100px;
            background-color: cyan;
        }
    </style>
</head>
<body>
    <div class="purple">
        I am positioned and parent
        <div class="cyan"> I am absolute element </div>
    </div>
</body>
</html> -->

Output:

Explanation: Here we can see child element has adjusted itself according to parent and no extra space is assign to it.

2nd Case: When the parent element is not positioned.

<!--
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        .purple {
            position: static;
            height: 200px;
            width: 200px;
            color: black;
            font-size: 1.5rem;
            padding: 10px;
            background-color: purple;
        }
        .cyan {
            position: absolute;
            bottom: 10px;
            left: 70px;
            font-size: 1.5rem;
            padding: 10px;
            height: 100px;
            width: 100px;
            background-color: cyan;
        }
    </style>
</head>
<body>
    <div class="purple">
        I am not-positioned and parent
        <div class="cyan"> I am absolute element </div>
    </div>
</body>
</html> -->

Output:

Explanation: As the parent is not positioned, the child element will try to adjust itself relative to nearest positioned ancestor. Here nearest positioned ancestor is <HTML> so element gets adjust according to <HTML>.

# position

Fixed Fixed element does not follow normal document flow and positions themselves relative to <HTML> tag. This element always stick to the screen.

Example: In this example, we will use fixed css position property.

<!--
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        .purple {
            position: relative;
            height: 2000px;
            width: 200px;
            color: black;
            font-size: 1.5rem;
            font-family: sans-serif;
            padding: 10px;
            background-color: purple;
        }
        .cyan {
            position: fixed;
            top: 200px;
            left: 10px;
            padding: 10px;
            font-size: 1rem;
            color: black;
            height: 100px;
            width: 100px;
            background-color: cyan;
        }
    </style>
</head>
<body>
    <div class="purple">
        I am reference
        <div class="cyan">
            I am fixed element
        </div>
    </div>
</body>
</html> -->

Output:

You can see the fixed element remain at its position even after scrolling up and down.

position: sticky It’s kind of a little tricky but very easy to understand. We can think of sticky as a combination of relative and fixed. Remember fixed elements remain fixed at some position but the sticky element will behave relative to a certain point and after behave like a fixed.

Example: In this example, we will use the sticky css position property.

<!--
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        .purple {
            position: absolute;
            height: 2000px;
            width: 200px;
            color: black;
            font-size: 1.5rem;
            font-family: sans-serif;
            padding: 10px;
            background-color: purple;
        }
        .cyan {
            position: sticky;
            top: 10px;
            left: 0px;
            padding: 10px;
            font-size: 1rem;
            color: black;
            height: 100px;
            width: 100px;
            background-color: cyan;
            z-index: 2;
        }

        .yellow {
            padding: 10px;
            position: relative;
            height: 100px;
            width: 100px;
            background-color: yellow;
        }
    </style>
</head>
<body>
    <div class="purple">
        <div class="yellow">I am reference</div>
        <div class="cyan">
            I am sticky element
        </div>
        <div class="yellow">I am reference</div>
    </div>
</body>
</html> -->

Output:

Explanation: In the above output, you can see the sticky element behaves like a relative element until it reaches a particular offset. Then beyond that point, it sticks to the page and behaves like fixed (here that offset is 10px from top).

Note: In sticky left, right, top and bottom does not determine the position of the element in the relative state but it specifies at what position element should behave like fixed.

source:<https://www.geeksforgeeks.org/explain-the-positions-property-in-css/>
