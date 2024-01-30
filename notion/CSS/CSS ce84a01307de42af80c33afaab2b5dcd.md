# CSS

### 

CSS is the language we use to style a Web page.

- CSS stands for Cascading Style Sheets
- CSS describes how HTML elements are to be displayed on screen, paper, or in other media
- CSS saves a lot of work. It can control the layout of multiple web pages all at once
- External stylesheets are stored in CSS files

A CSS rule consists of a selector and a declaration block.

In this example all <p> elements will be center-aligned, with a red text color:

p {  color: red;  text-align: center;}

- `p` is a selector in CSS (it points to the HTML element you want to style: <p>).
- `color` is a property, and `red` is the property value
- `text-align` is a property, and `center` is the property value

# CSS Selectors

CSS selectors are used to "find" (or select) the HTML elements you want to style.

- Simple selectors (select elements based on name, id, class)
- [Combinator selectors](https://www.w3schools.com/css/css_combinators.asp) (select elements based on a specific relationship between them)
- [Pseudo-class selectors](https://www.w3schools.com/css/css_pseudo_classes.asp) (select elements based on a certain state)
- [Pseudo-elements selectors](https://www.w3schools.com/css/css_pseudo_elements.asp) (select and style a part of an element)
- [Attribute selectors](https://www.w3schools.com/css/css_attribute_selectors.asp) (select elements based on an attribute or attribute value)

**The CSS element Selector**

The element selector selects HTML elements based on the element name.

# Example

```html
<p> elements on the page will be center-aligned, with a red text color:

p {  text-align: center;  color: red;}
```

# The CSS id Selector

The id selector uses the id attribute of an HTML element to select a specific element.

The id of an element is unique within a page, so the id selector is used to select one unique element!

To select an element with a specific id, write a hash (#) character, followed by the id of the element.

# Example

The CSS rule below will be applied to the HTML element with id="para1":

**Note:** An id name cannot start with a number!

```html
#para1 {  text-align: center;  color: red;}
```

# The CSS class Selector

The class selector selects HTML elements with a specific class attribute.

To select elements with a specific class, write a period (.) character, followed by the class name.

# Example

In this example all HTML elements with class="center" will be red and center-aligned:

```html
.center {  text-align: center;  color: red;}
```

You can also specify that only specific HTML elements should be affected by a class.

# Example

In this example only <p> elements with class="center" will be red and center-aligned:

```html
p.center {  text-align: center;  color: red;}
```

# CSS Selectors

A CSS selector selects the HTML element(s) you want to style.

# CSS Selectors

CSS selectors are used to "find" (or select) the HTML elements you want to style.

We can divide CSS selectors into five categories:

- Simple selectors (select elements based on name, id, class)
- [Combinator selectors](https://www.w3schools.com/css/css_combinators.asp) (select elements based on a specific relationship between them)
- [Pseudo-class selectors](https://www.w3schools.com/css/css_pseudo_classes.asp) (select elements based on a certain state)
- [Pseudo-elements selectors](https://www.w3schools.com/css/css_pseudo_elements.asp) (select and style a part of an element)
- [Attribute selectors](https://www.w3schools.com/css/css_attribute_selectors.asp) (select elements based on an attribute or attribute value)

This page will explain the most basic CSS selectors.

---

# The CSS element Selector

The element selector selects HTML elements based on the element name.

# Example

Here, all <p> elements on the page will be center-aligned, with a red text color:

p {  text-align: center;  color: red;}

# The CSS id Selector

The id selector uses the id attribute of an HTML element to select a specific element.

The id of an element is unique within a page, so the id selector is used to select one unique element!

To select an element with a specific id, write a hash (#) character, followed by the id of the element.

# Example

The CSS rule below will be applied to the HTML element with id="para1":

#para1 {  text-align: center;  color: red;}

**Note:** An id name cannot start with a number!

---

# The CSS class Selector

The class selector selects HTML elements with a specific class attribute.

To select elements with a specific class, write a period (.) character, followed by the class name.

# Example

In this example all HTML elements with class="center" will be red and center-aligned:

.center {  text-align: center;  color: red;}

You can also specify that only specific HTML elements should be affected by a class.

# Example

In this example only <p> elements with class="center" will be red and center-aligned:

p.center {  text-align: center;  color: red;}

HTML elements can also refer to more than one class.

# Example

In this example the <p> element will be styled according to class="center" and to class="large":

<p class="center large">This paragraph refers to two classes.</p>

**Note:** A class name cannot start with a number!

# The CSS Universal Selector

The universal selector (*) selects all HTML elements on the page.

# Example

The CSS rule below will affect every HTML element on the page:

- { text-align: center; color: blue;}

# The CSS Grouping Selector

The grouping selector selects all the HTML elements with the same style definitions.

Look at the following CSS code (the h1, h2, and p elements have the same style definitions):

h1 {  text-align: center;  color: red;}h2 {  text-align: center;  color: red;}p {  text-align: center;  color: red;}

It will be better to group the selectors, to minimize the code.

To group selectors, separate each selector with a comma.

# Example

In this example we have grouped the selectors from the code above:

h1, h2, p {  text-align: center;  color: red;}

**Test Yourself With Exercises
Exercise:**
Set the text color of all <p> elements to red.

`<style>
 {
   red;
}
</style>`

# All CSS Simple Selectors

| Selector | Example | Example description |
| --- | --- | --- |
| https://www.w3schools.com/cssref/sel_id.asphttps://www.w3schools.com/cssref/sel_id.asp | #firstname | Selects the element with id="firstname" |
| https://www.w3schools.com/cssref/sel_class.asphttps://www.w3schools.com/cssref/sel_class.asp | .intro | Selects all elements with class="intro" |
| https://www.w3schools.com/cssref/sel_element_class.asp | p.intro | Selects only <p> elements with class="intro" |
| https://www.w3schools.com/cssref/sel_all.asp | * | Selects all elements |
| https://www.w3schools.com/cssref/sel_element.asp | p | Selects all <p> elements |
| https://www.w3schools.com/cssref/sel_element_comma.asp | div, p | Selects all <div> elements and all <p> elements |

# CSS Backgrounds

The CSS background properties are used to add background effects for elements.

In these chapters, you will learn about the following CSS background properties:

- `background-color`
- `background-image`
- `background-repeat`
- `background-attachment`
- `background-position`
- `background` (shorthand property)

---

# CSS background-color

The `background-color` property specifies the background color of an element.

# Example

The background color of a page is set like this:

body {  background-color: lightblue;}

With CSS, a color is most often specified by:

- a valid color name - like "red"
- a HEX value - like "#ff0000"
- an RGB value - like "rgb(255,0,0)"

# Other Elements

You can set the background color for any HTML elements:

# Example

Here, the <h1>, <p>, and <div> elements will have different background colors:

h1 {  background-color: green;}div {  background-color: lightblue;}p {  background-color: yellow;}

# Opacity / Transparency

The `opacity` property specifies the opacity/transparency of an element. It can take a value from 0.0 - 1.0. The lower value, the more transparent:

opacity 1

opacity 0.6

opacity 0.3

opacity 0.1

# Example

div {  background-color: green;  opacity: 0.3;}

**Note:** When using the `opacity` property to add transparency to the background of an element, all of its child elements inherit the same transparency. This can make the text inside a fully transparent element hard to read.

# Transparency using RGBA

If you do not want to apply opacity to child elements, like in our example above, use **RGBA** color values. The following example sets the opacity for the background color and not the text:

100% opacity

60% opacity

30% opacity

10% opacity

# Example

div {  background: rgba(0, 128, 0, 0.3) /* Green background with 30% opacity */}

# The CSS Background Color Property

| Property | Description |
| --- | --- |
| https://www.w3schools.com/cssref/pr_background-color.asp | Sets the background color of an element |

# CSS Margins

---

Margins are used to create space around elements, outside of any defined borders.

---

This element has a margin of 70px.

# CSS Margins

The CSS `margin` properties are used to create space around elements, outside of any defined borders.

With CSS, you have full control over the margins. There are properties for setting the margin for each side of an element (top, right, bottom, and left).

---

# Margin - Individual Sides

CSS has properties for specifying the margin for each side of an element:

- `margin-top`
- `margin-right`
- `margin-bottom`
- `margin-left`

All the margin properties can have the following values:

- auto - the browser calculates the margin
- *length* - specifies a margin in px, pt, cm, etc.
- *%* - specifies a margin in % of the width of the containing element
- inherit - specifies that the margin should be inherited from the parent element

**Tip:** Negative values are allowed.

# Example

Set different margins for all four sides of a <p> element:

p {  margin-top: 100px;  margin-bottom: 100px;  margin-right: 150px;  margin-left: 80px;}

# CSS Padding

Padding is used to create space around an element's content, inside of any defined borders.

This element has a padding of 70px.

# CSS Padding

The CSS `padding` properties are used to generate space around an element's content, inside of any defined borders.

With CSS, you have full control over the padding. There are properties for setting the padding for each side of an element (top, right, bottom, and left).

---

# Padding - Individual Sides

CSS has properties for specifying the padding for each side of an element:

- `padding-top`
- `padding-right`
- `padding-bottom`
- `padding-left`

All the padding properties can have the following values:

- *length* - specifies a padding in px, pt, cm, etc.
- *%* - specifies a padding in % of the width of the containing element
- inherit - specifies that the padding should be inherited from the parent element

**Note:** Negative values are not allowed.

# Example

Set different padding for all four sides of a <div> element:

div {  padding-top: 50px;  padding-right: 30px;  padding-bottom: 50px;  padding-left: 80px;}

# CSS Lists

# Unordered Lists:

- Coffee
- Tea
- Coca Cola
- Coffee
- Tea
- Coca Cola

**Ordered Lists:**
1. Coffee
2. Tea
3. Coca Cola
1. Coffee
2. Tea
3. Coca Cola

---

# HTML Lists and CSS List Properties

In HTML, there are two main types of lists:

- unordered lists (<ul>) - the list items are marked with bullets
- ordered lists (<ol>) - the list items are marked with numbers or letters

The CSS list properties allow you to:

- Set different list item markers for ordered lists
- Set different list item markers for unordered lists
- Set an image as the list item marker
- Add background colors to lists and list items

---

# Different List Item Markers

The `list-style-type` property specifies the type of list item marker.

The following example shows some of the available list item markers:

# Example

```html
ul.a {  list-style-type: circle;}
ul.b {  list-style-type: square;}
ol.c {  list-style-type: upper-roman;}
ol.d {  list-style-type: lower-alpha;}
```

# CSS Layout - display: inline-block

# The display: inline-block Value

Compared to `display: inline`, the major difference is that `display: inline-block` allows to set a width and height on the element.

Also, with `display: inline-block`, the top and bottom margins/paddings are respected, but with `display: inline` they are not.

Compared to `display: block`, the major difference is that `display: inline-block` does not add a line-break after the element, so the element can sit next to other elements.

The following example shows the different behavior of `display: inline`, `display: inline-block` and `display: block`:

# Example

```html
span.a {  display: inline; /* the default for span */ 
 width: 100px;  height: 100px;  padding: 5px;  border: 1px solid blue; 
 background-color: yellow;}span.b {  display: inline-block;  width: 100px; 
 height: 100px;  padding: 5px;  border: 1px solid blue; 
 background-color: yellow;}span.c {  display: block;  width: 100px; 
 height: 100px;  padding: 5px;  border: 1px solid blue;  background-color: yellow;}
```