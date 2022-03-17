# HTML-Workspace
this is test account for HTML practice
![html-tutorial](https://user-images.githubusercontent.com/92047366/158020964-231ceb9a-f34b-4c08-a131-20678f350760.png)

HTML is the standard markup language for creating Web pages.

What is HTML?
HTML stands for Hyper Text Markup Language
HTML is the standard markup language for creating Web pages
HTML describes the structure of a Web page
HTML consists of a series of elements
HTML elements tell the browser how to display the content
HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.
A Simple HTML Document
Example
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
Example Explained
The <!DOCTYPE html> declaration defines that this document is an HTML5 document
The <html> element is the root element of an HTML page
The <head> element contains meta information about the HTML page
The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
The <h1> element defines a large heading
The <p> element defines a paragraph
What is an HTML Element?
An HTML element is defined by a start tag, some content, and an end tag:

<tagname> Content goes here... </tagname>
The HTML element is everything from the start tag to the end tag:

<h1>My First Heading</h1>
<p>My first paragraph.</p>
Start tag	Element content	End tag
<h1>	My First Heading	</h1>
<p>	My first paragraph.	</p>
<br>	none	none
Note: Some HTML elements have no content (like the <br> element). These elements are called empty elements. Empty elements do not have an end tag!

Web Browsers
The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.

A browser does not display the HTML tags, but uses them to determine how to display the document:
![img_chrome](https://user-images.githubusercontent.com/92047366/158020862-3350fdf0-67db-4582-beef-370869ffa156.png)
HTML Page Structure
Below is a visualization of an HTML page structure:
  <html>
<head>
<title>Page title</title>
</head>
<body>
<h1>This is a heading</h1>
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
</body>
</html>
 <br>
  <br>
  <h1>CSS</h1>
  ![download](https://user-images.githubusercontent.com/92047366/158849390-6881fc44-178a-41f1-9af2-7e879c50b654.png)
CSS is the language we use to style a Web page.

  <b>What is CSS?</b>
CSS stands for Cascading Style Sheets
CSS describes how HTML elements are to be displayed on screen, paper, or in other media
CSS saves a lot of work. It can control the layout of multiple web pages all at once
External stylesheets are stored in CSS files
CSS Demo - One HTML Page - Multiple Styles!
Here we will show one HTML page displayed with four different stylesheets. Click on the "Stylesheet 1", "Stylesheet 2", "Stylesheet 3", "Stylesheet 4" links below to see the different styles:



  <b>Why Use CSS?</b>
CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.

  <b>CSS Example</b>
body {
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: verdana;
  font-size: 20px;
}
  <b>CSS Solved a Big Problem</b>
HTML was NEVER intended to contain tags for formatting a web page!

HTML was created to describe the content of a web page, like:

<h1>This is a heading</h1>

<p>This is a paragraph.</p>

When tags like <font>, and color attributes were added to the HTML 3.2 specification, it started a nightmare for web developers. Development of large websites, where fonts and color information were added to every single page, became a long and expensive process.

To solve this problem, the World Wide Web Consortium (W3C) created CSS.

CSS removed the style formatting from the HTML page!

If you don't know what HTML is, we suggest that you read our HTML Tutorial.

CSS Saves a Lot of Work!
The style definitions are normally saved in external .css files.

With an external stylesheet file, you can change the look of an entire website by changing just one file!
  

