`<!DOCTYPE html>` -  we need to start every html code with this keyword which defines that this is an html document. Html = Hyper Text Markup Language

`<html>`, `</html>` - is the root element of an HTML document. 

`<head>`, `</head>` - represents a collection of metadata for the document. This includes tags like : 

- `<header>`, `</header>` is a new alternative to "`<div class>`". It represents a container for introductory content or a set of navigational links which are written using `<nav>`, `</nav>` tags. Header usually contains one or more "`<h1>-<h6>`" elements, logo and/or autorship informations. 
- `<title>`, `</title>` which represents the document's name;
- `<meta charset="UTF-8">` which specifies which character set a website is written with. UTF-8 stands for Universal Character Set + Transformation Format -8bit. This character set is mostly used in european countries where there are no special characters needed.
- `<meta name="description" content="My WebApplication">` 
- `<link rel="stylesheet" href="stylesheet.css">` this allow the author to link document to other resources. In this example to a "stylesheet.css". 

`<section>`, `</section>` defines sections in a document, such as chapters, headers, footers, or any other sections.

`<main>`, `</main>` tags tells the browser what's the main content of the document

`<table>`, `</table>` - table comes from tabular data. It stores data in form of a table. 

`<tr>`, `</tr>` - represents a row of cells in a table.

`<th>`, `</th>` - represents the header cell of a table.

`<td>`, `</td>` - represents the data cell of a table.

`<article>`, `</article>` tags has been introduced with the new HTML5. It has almost the same purpose as "`<p>`, `</p>`" tags. It specifies independent, self-containted content that can be distributed independently from the rest of the site. Same examples with this tags can include forum posts, blog posts, comments etc.

`<aside>`, `</aside>` tags has been introduced with the new HTML5 version. This is used to relate content aside from the content it is placed in. It should be related to the surrounding content.

`<ul>`, `</ul>` tags creates unordered lists, such as bullet points, and it has been introduced with HTML5.

`<li>`, `</li>` means list item and these tags have been introduced with HTML5.

`<ol>`, `</ol>` ol = organised list. These tags are used to create organised lists, such as "1, 2 , 3 ...n" or "a, b, c, ... z". They are also new tags from HTML5.
 
`<style>`, `</style>` tags can also be used from inside the document itself, but it's not best practice as it can get pretty messy and hard to follow.

`<body>`, `</body>` - these tags defines the document's body. They can include content such as text, hyperlinks, images, tables, lists and so on. Let's see some tags that are included inside the "body":

- `<h1>`, `</h1>` - this represents document's heading and it can vary from h1 to h6 where h1 is the biggest size and h6 the lowest.
- `<div class ="...">`, `</div>` is used when you want to use the styles on multiple elements;
- `<div id ="...">`, `</div>` is used when you want to use the styles on a single element;
- `<a href="link here" target="..."`, `</a>` when the "a" element has a "href" attribute, then it represents a hyperlink labeled by its contents;
- `<p>`, `</p>` - represents a paragraph;
- `<img src="insert source here" alt="insert image name here">` - this represents an image and src is the source of the image and alt is the name of the image;
- `<script src="index.js">`, `</script>` - this allow users to insert dynamic script and data blocks in their code from another resource.

`<footer>`, `</footer>` tags are used for copyright, links and some other informations like that. They are also new from HTML5.
