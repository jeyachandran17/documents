## HTML Documents

### What is HTML ?

1. HTML stands for `HyperText Markup Language`
2. It's standard markup language for creating web pages
3. It's describe the structure of web pages.
4. HTML elements tell the browser how to display the content
5. HTML elements label pieces of content such as `"this is heading", "this is paragraph" and "this is link", etc,..`

<hr>

### HTML Elements

1. The HTML elements is everything from the start tag to end tag

```
Example:
    
    <h3> welcome to html learning </h3>

```
- `<h3>` --> it's a starting tag   
- `</h3>` -->  it's a ending tag

2. some tags are single tags
    - like : `<br>` `<hr>` 

<hr>

### HTML Attribute

1. All HTML elements can have `attributes`.
2. Attributes provide `additional information` about elements.
3. Attributes are `always specified in the start tag`.
4. Attributes usually come in name/value pairs 
    - like :  `name="value"`
```
Example :

    <p style="color:red;"> welcome to html learning </p>
```

- output : 
    
    ![welcome to html](./pictures/welcome-to-html.png)

    - The `style` attribute is used to add the styles to an element, 
    - such as `color, font, size, and more...`.

<hr>

### HTML tags

- HTML tags help web browsers convert HTML documents into web pages

-  For example : the `<p>` tag is used to organize text content into paragraph

<hr>

### `<!DOCTYPE html>` tag

1. the `<!DOCTYPE html>` tag is described to HTML5 documents
2. the HTML5 documents must start with a `<!DOCTYPE html>` declaration.

<hr>

### `<a>` tag 

1. The `<a>` tag defines a hyperlink, which is used to link from one page to another.

2. The `most important attribute` of the `<a>` element is the href attribute, which indicates the link's destination.

<hr>

### HTML commant tag

- you can add your commants in HTML file
```
<!-- Write your comments here -->
``` 
<hr>

### `<abbr>` tag

- The `<abbr>` tag defines an abbreviation
- Example : the `<abbr title="HyperText Markup Language">HTML</abbr>` is used to create a web pages --> the hover the HTML text and show the abbreviation.

<hr>

### `<b>` tag

- The `<b>` tag specifies bold text

<hr>

### `<br>` tag

- The `<br>` tag inserts a single line break and it's an empty tag.

<hr>

### `<div>` tag

1. The `<div>` tag defines a division or a section in an HTML document.

2. The `<div>` tag is used as a container for HTML element

<hr>

### `<hr>` tag

1. The `<hr>` element is most often displayed as a horizontal line. 
2. it's used to separate content in an HTML page.

<hr>

### `<audio>` tag

1. The `<audio>` tag is used to embed sound content in a document, such as `music or other audio` streams.

2. The `<audio>` tag contains one or more `<source>` tags with different audio sources. 

3. The browser will choose the first source it supports.

4. There are supported audio formats in HTML documents: `MP3, WAV, and OGG`

5. Note : `<audio condrols autoplay>`The autoplay attribute not working some browser      

<hr>

### heading tags

1. The `<h1>` to `<h6>` tags are used to define HTML headings. 

2. `<h1>` defines the most important heading. 

3. `<h6>` defines the least important heading.

<hr>

### `<head>` tag

- The `<head>` element is a container for metadata and is `placed between the <html> tag to <body> tag`

<hr>

### `<img>` tag

1. The `<img>` tag is used to embed an image in an HTML page

2. The most two importent attribute is `src and alt`

    - `src` is Specifies the path to the image
    - `alt` is Specifies an alternate text for the imag
<hr>

### `<link>` tag

1. The `<link>` tag defines the relationship between the current document and an external resource.

2. The `<link>` tag is most often used to link to external documents ( or ) to add a favicon to your website.

<hr>

### `<q>` tag

- This tag defines a short quotation

<hr>

### `<section>` tag

- This tag defines a section in a document and it's also same purpose of `div and article` tag.

<hr>

### `<span>` tag

1. This tag is an inline container.
2. it's used to mark up a part of a text.

<hr>

### `<progress>` tag

- This tag represents the completion progress of a task.

<hr>

### `<select>` tag

1. The `<select>` element is used to create a drop-down list.

2. The `<select>` element is most often used in a form, to collect user input.

<hr>

### HTML Formatting Elements
Formatting elements were designed to display special types of text:
```
        <b> Bold text </b>   
        <strong> Important text </strong>   
        <i> italic text </i>
        <em> Emphasized text </em>
        <mark> Marked text </mark> 
        <small> smaller text </small> 
        <del> Deleted text </del> 
        <ins> Inserted text </ins> 
        <sub> Subscript text </sub>
        <sup> Superscript text </sup>

```
- Sample :

    ![html formatting](./pictures/html-formtting.png)


<hr>

### HTML Block and Inline Elements

1. Block elements
    - A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element.

    - A block-level element always takes up the full width available

    - Example : `<p> and <div>,.etc`

2. Inline elements

    - An inline element does not start on a new line.

    - An inline element only takes up as much width as necessary.

    - Example : `<span> and <b>,.etc`

<hr>

### HTML class Attribute
1. The HTML class attribute is used to specify a class for an HTML element.

2. Multiple HTML elements can share the same class.

    - Example : `<p class="first_paragraph">`

<hr>

### HTML Forms

1. An HTML form is used to collect user input. 
2. The user input is most often sent to a server for processing.
3. it's use the element is `<form></form>`

<hr>

### `<form>` elements

1. he HTML `<form>` element is used to create an HTML form for user input
2. The `<form>` element is a container for different types of input elements 
3. such as: `text fields, checkboxes, radio buttons, submit buttons, etc`

<hr>

### HTML Canvas Graphics

1. The HTML `<canvas>` element is used to draw graphics, on the fly, via JavaScript.

2. The `<canvas>` element is only a container for graphics. You must use JavaScript to actually draw the graphics.

3. Canvas has several methods for `drawing paths, boxes, circles, text, and adding images`.

### HTML using CSS : 

1. CSS can be added to HTML documents in 3 ways:
    - `Inline` - by using the `style` attribute inside HTML elements
    - `Internal` - by using a `<style>` element in the <head> section
    - `External` - by using a `<link>` element to link to an external CSS file

```
Example :

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML & CSS</title>
    <link rel="stylesheet" href="./style.css">  <!-- this element is "External CSS" with linked to html file  -->
</head>
<!-- this element is "internal CSS" -->
<style>
    h3{
        font-family:cursive;
        color: dodgerblue;
    }
</style>
<body>
    <h3>welcome to html & css learning</h3>
    <p style="color:red">everyone has do be creating the web pages is using HRML</p>    <!-- this element is "inline CSS" -->
    <p>happy coding...</p>
</body>
</html>
```

- Output : 

    ![welcome to html & css](./pictures/welcome-to-html-css.png)

<hr>

### HTML using javascript

1. JavaScript makes HTML pages more dynamic and interactive.

2. `Internal` - by using a `<script>` element in the <head> section

<hr>



