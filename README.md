`<!DOCTYPE html>` -  we need to start every html code with this keyword which defines that this is an html document. Html = Hyper Text Markup Language

`<html>`, `</html>` - is the root element of an HTML document. 

`<head>`, `</head>` - represents a collection of metadata for the document. This includes tags like : 

- `<title>`, `</title>` which represents the document's name;
- `<meta charset="UTF-8">` which specifies which character set a website is written with. UTF-8 stands for Universal Character Set + Transformation Format -8bit. This character set is mostly used in european countries where there are no special characters needed.
- `<meta name="description" content="My WebApplication">` 
- `<link rel="stylesheet" href="stylesheet.css">` this allow the author to link document to other resources. In this example to a "stylesheet.css". 

`<style>`, `</style>` tags can also be used from inside the document itself, but it's not best practice as it can get pretty messy and hard to follow.

`<body>`, `</body>` - these tags defines the document's body. They can include content such as text, hyperlinks, images, tables, lists and so on. Let's see some tags that are included inside the "body":

- `<h1>`, `</h1>` - this represents document's heading and it can vary from h1 to h6 where h1 is the biggest size and h6 the lowest.
- `<div class ="...">`, `</div>` is used when you want to use the styles on multiple elements;
- `<div id ="...">`, `</div>` is used when you want to use the styles on a single element;
- `<a href="link here" target="..."`, `</a>` when the "a" element has a "href" attribute, then it represents a hyperlink labeled by its contents;
- `<p>`, `</p>` - represents a paragraph;
- `<img src="insert source here" alt="insert image name here">`, `</img>` - this represents an image and src is the source of the image and alt is the name of the image;
- `<script src="index.js">`, `</script>` - this allow users to insert dynamic script and data blocks in their code from another resource.
