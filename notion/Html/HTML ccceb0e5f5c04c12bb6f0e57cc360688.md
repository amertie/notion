# HTML

# HTML Introduction

HTML is the standard markup language for creating Web pages.

# What is HTML?

- HTML stands for Hyper Text Markup Language
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

# A Simple HTML Document

# Example

<!DOCTYPE html><html><head><title>Page Title</title></head><body><h1>My First Heading</h1><p>My first paragraph.</p></body></html>

# Example Explained

- The `<!DOCTYPE html>` declaration defines that this document is an HTML5 document
- The `<html>` element is the root element of an HTML page
- The `<head>` element contains meta information about the HTML page
- The `<title>` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
- The `<body>` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- The `<h1>` element defines a large heading
- The `<p>` element defines a paragraph

---

# What is an HTML Element?

An HTML element is defined by a start tag, some content, and an end tag:

<tagname> Content goes here... </tagname>

The HTML **element** is everything from the start tag to the end tag:

<h1>My First Heading</h1>

<p>My first paragraph.</p>

| Start tag | Element content | End tag |
| --- | --- | --- |
| <h1> | My First Heading | </h1> |
| <p> | My first paragraph. | </p> |
| <br> | none | none |

**Note:** Some HTML elements have no content (like the <br> element). These elements are called empty elements. Empty elements do not have an end tag!

---

---

# Web Browsers

The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.

A browser does not display the HTML tags, but uses them to determine how to display the document:

# HTML Page Structure

Below is a visualization of an HTML page structure:

<html><head>

<title>Page title</title>

</head><body>

<h1>This is a heading</h1>

<p>This is a paragraph.</p>

<p>This is another paragraph.</p>

</body></html>

**Note:** The content inside the <body> section will be displayed in a browser. The content inside the <title> element will be shown in the browser's title bar or in the page's tab.

# HTML Attributes

HTML attributes provide additional information about HTML elements.

# HTML Attributes

- All HTML elements can have **attributes**
- Attributes provide **additional information** about elements
- Attributes are always specified in **the start tag**
- Attributes usually come in name/value pairs like: **name="value"**

# The href Attribute

The `<a>` tag defines a hyperlink. The `href` attribute specifies the URL of the page the link goes to:

# Example

<a href="https://www.w3schools.com">Visit W3Schools</a>

You will learn more about links in our [HTML Links chapter](https://www.w3schools.com/html/html_links.asp).

# The src Attribute

The `<img>` tag is used to embed an image in an HTML page. The `src` attribute specifies the path to the image to be displayed:

# Example

<img src="img_girl.jpg">

There are two ways to specify the URL in the `src` attribute:

**1. Absolute URL** - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

**Notes:** External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

**2. Relative URL** - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

**Tip:** It is almost always best to use relative URLs. They will not break if you change domain.

---

# The width and height Attributes

The `<img>` tag should also contain the `width` and `height` attributes, which specify the width and height of the image (in pixels):

# Example

<img src="img_girl.jpg" width="500" height="600">

---

# The alt Attribute

The required `alt` attribute for the `<img>` tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the `src` attribute, or if the user uses a screen reader.

# Example

<img src="img_girl.jpg" alt="Girl with a jacket">

# Example

See what happens if we try to display an image that does not exist:

<img src="img_typo.jpg" alt="Girl with a jacket">

You will learn more about images in our [HTML Images chapter](https://www.w3schools.com/html/html_images.asp).

# The style Attribute

The `style` attribute is used to add styles to an element, such as color, font, size, and more.

# Example

<p style="color:red;">This is a red paragraph.</p>

# HTML Div Element

---

The `<div>` element is used as a container for other HTML elements.

---

# The <div> Element

The `<div>` element is by default a block element, meaning that it takes all available width, and comes with line breaks before and after.

# Example

A <div> element takes up all available width:

Lorem Ipsum <div>I am a div</div> dolor sit amet.

# Result

Lorem Ipsum

I am a div

dolor sit amet.

The `<div>` element has no required attributes, but `style`, `class` and `id` are common.

---

# <div> as a container

The `<div>` element is often used to group sections of a web page together.

# HTML id Attribute

The HTML `id` attribute is used to specify a unique id for an HTML element.

You cannot have more than one element with the same id in an HTML document.

# Using The id Attribute

The `id` attribute specifies a unique id for an HTML element. The value of the `id` attribute must be unique within the HTML document.

The `id` attribute is used to point to a specific style declaration in a style sheet. It is also used by JavaScript to access and manipulate the element with the specific id.

The syntax for id is: write a hash character (#), followed by an id name. Then, define the CSS properties within curly braces {}.

In the following example we have an `<h1>` element that points to the id name "myHeader". This `<h1>` element will be styled according to the `#myHeader` style definition in the head section:

# Example

<!DOCTYPE html><html><head><style>#myHeader {  background-color: lightblue;  color: black;  padding: 40px;  text-align: center;}</style></head><body><h1 id="myHeader">My Header</h1></body></html>

**Note:** The id name is case sensitive!

**Note:** The id name must contain at least one character, cannot start with a number, and must not contain whitespaces (spaces, tabs, etc.).

# Difference Between Class and ID

A class name can be used by multiple HTML elements, while an id name must only be used by one HTML element within the page:

# Example

<style>/* Style the element with the id "myHeader" */**#myHeader** {  background-color: lightblue;  color: black;  padding: 40px;  text-align: center;}/* Style all elements with the class name "city" */**.city** {  background-color: tomato;  color: white;  padding: 10px;}</style><!-- An element with a unique id --><h1 id="myHeader">My Cities</h1><!-- Multiple elements with same class --><h2 class="city">London</h2><p>London is the capital of England.</p><h2 class="city">Paris</h2><p>Paris is the capital of France.</p><h2 class="city">Tokyo</h2><p>Tokyo is the capital of Japan.</p>

# London

London is the capital city of England.

London has over 13 million inhabitants.

### HTML TAGS

## 1.heading 1 tag

```html
<h1> bold </h1>
```

## 2.label tag

```html
<label> </label>
```

## 3. Div tag

```html
<div> 
<h1> heading 
</h1>
<p> paragraph </p>
 </div>
```

## 4. image tag

```html
<img src="smile.jpg" alt="smile" width="23" height="55">
```

## 5. Input tag

```html
<input type="text" id="fname" name="name"> 
```

## 6.ins / inserted tag

```html
<ins> red </ins>
```

## 7. iframe tag

```html
<iframe src="https://www.w3schools.com" title="w3schools"> </iframe>
```

## 8. html form

```html
<form> 
<label for="fname"> fname: </label> <br>
<input type="text" id="fname" name="fname">
</form>form element 
```

## 9. typewrite tags

```html
<tt> </tt>
```

## 10. dialog tag

```html
<dialog> </dialog>
```

## 11. span

```html
<span> </span>
```