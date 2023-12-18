HTML : hyper text markup language


HTML  --->  markup lANGUAGE ??

In HTML everything is created by using Tags hence html is known as Markup language.

As we all know HTML is a language of the web. It’s used to design the web pages or we can say structure the page layouts of a website. HTML stands for HYPERTEXT MARKUP LANGUAGE, as its full form suggests it’s not any programming language, a markup language. So, while the execution of HTML code we can’t face any such error. In real HTML code wasn’t compiled or interpreted because HTML code was rendered by the browser. which is similar to the compilation of a program. Html content is parched through the browser to display the content of HTML.

HTML DOCUMENT

HTML DOCUMENTS STRUCTURE

Html used predefined tags and attributes to tell the browser how to display content, means in which format, style, font size, and images to display. Html is a case insensitive language. Case insensitive means there is no difference in upper case and lower case ( capital and small letters) both treated as the same, for r example ‘D’ and ‘d’ both are the same here.
There are generally two types of tags in HTML:

Paired Tags: These tags come in pairs. That is they have both opening(< >) and closing(</ >) tags.
Empty Tags: These tags do not require to be closed.

Below is an example of a (<b>) tag in HTML, which tells the browser to bold the text inside it.

paired tag --> <b>Welcome to html tutorials</b>
Empty tag ---> <img>, <br>

Tags and attributes: Tags are individuals of html structure, we have to open and close any tag with a forward slash like this <h1> </h1>. There are some variations with the tag some of them are self-closing tag which isn’t required to close and some are empty tag where we can add any attributes in it. Attributes are additional properties of html tags that define the property of any html tags. i.e. width, height, controls, loops, input, and autoplay. These attributes also help us to store information in meta tags by using name, content, and type attributes. Html documents structured mentioned below:

Structure of an HTML Document
An HTML Document is mainly divided into two parts:

HEAD: This contains the information about the HTML document. For Example, the Title of the page, version of HTML, Meta Data, etc.
BODY: This contains everything you want to display on the Web Page.

HTML Document Structure

Let us now have a look at the basic structure of HTML. That is the code that is a must for every webpage to have:

<!DOCTYPE html>
<!-- Defines types of documents : Html 5.O  -->
<!DOCTYPE html>
<!-- Defines types of documents : Html 5.O -->
<html lang="en">
    <!-- DEfines languages of content : English -->
    <head>
    <!-- Information about website and creator -->
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <!-- Defines the compatibility of version with browser -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- for make website responsive -->
    <meta name="author" content="Mr.X">
    <meta name="Linkedin profile" content="WWW.linkedin.com/Mr.X_123" >
    <!-- To give information about author or owner -->
    <meta name="description "
    content="A better place to learn computer science">
    <!-- to explain about website in few words -->
    <title>GeeksforGeeks</title>
    <!-- Name of website or content to display -->
</head>
<body>
    <!-- Main content of website -->
    <h1>GeeksforGeeks</h1>
<p>A computer science portal for geeks</p>
</body>
</html>
Every Webpage must contain this code. Below is the complete explanation of each of the tags used in the above piece of HTML code:
<!DOCTYPE html>: This tag is used to tells the HTML version. This currently tells that the version is HTML 5.0
<html>  </html> : <html> is a root element of html.  It’s a biggest and main element  in complete  html language, all the tags , elements and attributes  enclosed in it or we can say wrap init , which is used to structure a web page. <html> tag is parent tag of <head> and  <body>  tag , other tags enclosed within <head > and <body>.  In <html > tag we use “lang” attributes to define languages of html page such as <html lang=”en”> here en represents English language. some of them are : es = Spanish , zh-Hans = Chinese, fr= french and el= Greek etc.
<head>: Head tag contains metadata, title, page CSS etc.  Data stored in the <head>  tag is not displayed to the user, it is just written for reference purposes and as a watermark of the owner.

Note: for better understanding refer above code of html.

 <title> = to store website name or content to be displayed.
 <link>   = To add/ link css( cascading style sheet)  file.
 <meta>   = 1. to store data about website, organisation ,
creator/ owner
            2. for responsive website via attributes
            3. to tell compatibility of html with browser
 <script> = to add javascript file.
<body>: A body tag is used to enclose all the data which a web page has from texts to links. All the content that you see rendered in the browser is contained within this element. Following tags and elements used in the body.

1 . <h1> ,<h2> ,<h3> to <h6> 2. <p> 3. <div> and <span> 4. <b>, <i> and<u> 5. <li>,<ul>and<ol>. 6. <img> , <audio> , <video> and<iframe> 7. <table> <th> , <thead>and<tr>.  
 8. <form> 9. <label> and <input> others……….
