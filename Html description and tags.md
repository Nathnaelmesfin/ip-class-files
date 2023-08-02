# HTML

# **What is HTML?**

HTML stands for **H**yper **T**ext **M**arkup **L**anguage

HTML is the **standard markup** language for Web pages

HTML **elements** are the building blocks of HTML pages

HTML elements are represented by **<> tags**

# HTML Elements

An HTML element is a **start** tag and an **end** tag with content in between:

<h1>This is a Heading</h1>

| Start tag | Element content | End tag |
| --- | --- | --- |
| <h1> | This is a Heading | </h1> |
| <p> | This is paragraph. | </p> |

# HTML Attributes

- HTML elements can have **attributes**
- Attributes provide **additional information** about the element
- Attributes come in name/value pairs like **charset="utf-8"**

# A Simple HTML Document

```jsx
<!DOCTYPE html>
<html lang="en">

<meta charset="utf-8">
<title>Page Title</title>

<body>
   <h1>This is a Heading</h1>
   <p>This is a paragraph.</p>
   <p>This is another paragraph.</p>
</body>

</html>
```

# Example Explained

HTML elements are the building blocks of HTML pages.

- The `<!DOCTYPE html>` declaration defines this document to be HTML5
- The `<html>` element is the root element of an HTML page
- The `lang` attribute defines the language of the document
- The `<meta>` element contains meta information about the document
- The `charset` attribute defines the character set used in the document
- The `<title>` element specifies a title for the document
- The `<body>` element contains the visible page content
- The `<h1>` element defines a large heading
- The `<p>` element defines a paragraph

---

# HTML Documents

All HTML documents must start with a document type declaration: `<!DOCTYPE html>`.

The HTML document itself begins with `<html>` and ends with `</html>`.

The visible part of the HTML document is between `<body>` and `</body>`.

# HTML Headings

HTML headings are defined with `<h1>` to `<h6>` tags.

`<h1>` defines the most important heading. `<h6>` defines the least important heading:

```jsx
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
```

# Example

```jsx
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

# HTML Paragraphs

HTML paragraphs are defined with `<p>` tags:

# Example

```jsx
<p>This is a paragraph.</p><p>This is another paragraph.</p>
```

# HTML Links

HTML links are defined with `<a>` tags:

# Example

```jsx
<a href="https://www.w3schools.com">This is a link</a>
```

The link's destination is specified in the `href` attribute.

# HTML Images

HTML images are defined with `<img>` tags.

The source file (`src`), alternative text (`alt`), `width`, and `height` are provided as attributes:

# Example

```jsx
<img src="img_w3schools.jpg" alt="W3Schools" style="width:120px;height:150px"
```

# HTML Buttons

HTML buttons are defined with `<button>` tags:

# Example

```jsx
<button>Click me</button>
```

# HTML Lists

HTML lists are defined with `<ul>` (unordered/bullet list) or `<ol>` (ordered/numbered list) tags, followed by `<li>` tags (list items):

# Example

```jsx
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```

# HTML Tables

An HTML table is defined with a `<table>` tag.

Table rows are defined with `<tr>` tags.

Table headers are defined with `<th>` tags. (bold and centered by default).

Table cells (data) are defined with `<td>` tags.

# Example

```jsx
<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
```

# Programming HTML

Every HTML element can have **attributes**.

For web development and programming, the most important attributes are **id** and **class.** These attributes are often used to address program based web page manipulations.

| Attribute | Example |
| --- | --- |
| id | <table id="table01" |
| class | <p class="normal"> |
| style | <p style="font-size:16px"> |
| data- | <div data-id="500"> |
| onclick | <input onclick="myFunction()"> |
| onmouseover | <a onmouseover="this.setAttribute('style','color:red')"> |


# **Html Tags**
```jsx
<!-- Defines a comment -->
<!--...--> 
<!--Defines the document type-->
<!DOCTYPE>
<!--Defines a hyperlink-->	
<a> 	
<!--Defines an abbreviation or an acronym-->
<abbr> 	
<!--Defines contact information for the author/owner of a document-->
<address> 	
<!--Defines an area inside an image map-->
<area> 	]
<!--Defines an article-->
<article> 	
<!--Defines content aside from the page content-->
<aside> 	
<!--Defines embedded sound content-->
<audio> 	
<!--Defines bold text-->
<b> 
<!--Specifies the base URL/target for all relative URLs in a document-->	
<base> 	
<!--Isolates a part of text that might be formatted in a different direction from other text outside it-->
<bdi> 	
<!--Overrides the current text direction-->
<bdo> 	
<!--Defines a section that is quoted from another source-->
<blockquote> 
<!--Defines the document's body-->	
<body> 	
<!--Defines a single line break-->
<br> 	
<!--Defines a clickable button-->
<button> 	
<!--Used to draw graphics, on the fly, via scripting (usually JavaScript)-->
<canvas> 	
<!--Defines a table caption-->
<caption> 	
<!--Defines the title of a work-->
<cite> 	
<!--Defines a piece of computer code-->
<code> 	
<col> 	<!--Specifies column properties for each column within a--> <colgroup> <!--element -->
<!--Specifies a group of one or more columns in a table for formatting-->
<colgroup> 	
<!--Adds a machine-readable translation of a given content-->
<data> 	
<!--Specifies a list of pre-defined options for input controls-->
<datalist> 	
<!--Defines a description/value of a term in a description list-->
<dd> 
<!--Defines text that has been deleted from a document-->
<del> 	
<!--Defines additional details that the user can view or hide-->
<details> 	
<!--Specifies a term that is going to be defined within the content-->
<dfn> 
<!--Defines a dialog box or window-->
<dialog> 	
<!--Defines a section in a document-->
<div> 	
<!--Defines a description list-->
<dl> 	
<!--Defines a term/name in a description list-->
<dt> 	
<!--Defines emphasized text -->
<em> 	
<!--Defines a container for an external application-->
<embed> 	
<!--Groups related elements in a form-->
<fieldset> 	
<figcaption> <!--Defines a caption for a--> <figure> <!--element-->
<!--Specifies self-contained content-->
<figure> 	
<!--Defines a footer for a document or section-->
<footer> 	
<!--Defines an HTML form for user input-->
<form> 	
<h1> <!--to--> <h6> <!--Defines HTML headings-->
<!--	Contains metadata/information for the document-->
<head> 
<!--Defines a header for a document or section-->
<header> 	
<!--Defines a thematic change in the content-->
<hr> 	
<!--Defines the root of an HTML document-->
<html> 	
<!--Defines a part of text in an alternate voice or mood-->
<i> 	
<!--Defines an inline frame-->
<iframe> 	
<!--Defines an image-->
<img> 	
<!--Defines an input control-->
<input> 	
<!--Defines a text that has been inserted into a document-->
<ins> 
<!--Defines keyboard input-->
<kbd> 	
<label> <!--Defines a label for an--> <input> <!--element-->
<legend> <!--Defines a caption for a--> <fieldset> <!--element-->
<!--Defines a list item-->
<li> 	
<!--Defines the relationship between a document and an external resource (most used to link to style sheets)-->
<link> 	
<!--Specifies the main content of a document-->
<main> 	
<!--Defines an image map-->
<map> 	
<!--Defines marked/highlighted text-->
<mark> 	
<!--Defines metadata about an HTML document-->
<meta> 
<!--Defines a scalar measurement within a known range (a gauge)-->	
<meter> 
<!--Defines navigation links-->	
<nav> 	
<!--Defines an alternate content for users that do not support client-side scripts-->
<noscript> 	
<!--Defines a container for an external application-->
<object> 	
<!--Defines an ordered list-->
<ol> 
<!--Defines a group of related options in a drop-down list-->	
<optgroup>
<!--Defines an option in a drop-down list--> 	
<option> 
<!--Defines the result of a calculation-->	
<output> 	
<!--Defines a paragraph-->
<p> 	
<!--Defines a parameter for an object-->
<param>
<!--Defines a container for multiple image resources-->
<picture>
<!--Defines preformatted text-->
<pre> 
<!--Represents the progress of a task-->	
<progress> 
<!--Defines a short quotation-->	
<q> 
<!--Defines what to show in browsers that do not support ruby annotations-->	
<rp> 
<!--Defines an explanation/pronunciation of characters (for East Asian typography)-->	
<rt> 
<!--Defines a ruby annotation (for East Asian typography)-->
<ruby> 	
<!--Defines text that is no longer correct-->
<s>
<!--Defines sample output from a computer program--> 	
<samp> 
<!--Defines a client-side script-->	
<script> </script>
<!-- Defines a section in a document-->	
<section> 	
<!--Defines a drop-down list-->
<select> 
<!--Defines smaller text-->	
<small> 	
<source> <!--Defines multiple media resources for media elements --> <video> <!--or--> <audio>
<!--Defines a section in a document-->
<span> 	
<!--Defines important text-->
<strong> 
<!--Defines style information for a document-->	
<style> </style>
<!--Defines subscripted text-->	
<sub> 	
<summary> <!--Defines a visible heading for a--> <details> <!--element-->
<!--Defines superscripted text-->
<sup> 	
<!--Defines a container for SVG graphics-->
<svg>
<!--Defines a table-->
<table> 
<!--Groups the body content in a table-->	
<tbody> 
<!--Defines a cell in a table-->
<td>
<!--Defines a container for content that should be hidden when the page loads--> 	
<template> 	
<!--Defines a multiline input control (text area)-->
<textarea> 
<!--Groups the footer content in a table-->	
<tfoot> 
<!--Defines a header cell in a table-->
<th> 
<!--Groups the header content in a table-->	
<thead> 
<!--Defines a specific time (or datetime)-->	
<time> 	
<!--Defines a title for the document-->
<title> 
<!--Defines a row in a table-->	
<tr> 	
<track> <!--Defines text tracks for media elements --> <video> <!--and--> <audio>
<!--Not supported in HTML5. Use CSS instead.-->
<tt>
<!--Defines some text that is unarticulated and styled differently from normal text--> 	
<u> 
<!--Defines an unordered list-->	
<ul> 
<!--Defines a variable-->	
<var>
<!--Defines embedded video content--> 	
<video> 
<!--Defines a possible line-break-->	
<wbr> 
```

