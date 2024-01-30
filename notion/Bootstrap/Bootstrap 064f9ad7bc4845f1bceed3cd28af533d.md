# Bootstrap

# **Creating Containers with Bootstrap**

Containers are the most basic layout element in Bootstrap and are required when using the grid system. Containers are basically used to wrap content with some padding. They are also used to align the content horizontally center on the page in case of fixed width layout.

Bootstrap provides three different types containers:

- `.container`, which has a max-width at each responsive breakpoint.
- `.container-fluid`, which has 100% width at all breakpoints.
- `.container-{breakpoint}`, which has 100% width until the specified breakpoint.

The table below illustrates how each container's max-width changes across each breakpoint.

For example, when using the `.container` class the actual width of the container will be 100% if the viewport width is <576px, 540px if the viewport width is ≥576px but <768px, 720px if the viewport width is ≥768px but <992px, 960px if the viewport width is ≥992px but <1200px, 1140px if the viewport width is ≥1200px but <1400px, and 1320px if the viewport width is ≥1400px.

Similarly, when you use the `.container-lg` class the actual width of the container will be 100% until the viewport width is <992px, 960px if the viewport width is ≥992px but <1200px, 1140px if the viewport width ≥1200px but <1400px, and 1320px if the viewport width is ≥1400px.

| ClassesBootstrap  Grid System | X-Small<576px | Small≥576px | Medium≥768px | Large≥992px | X-Large≥1200px | XX-Large≥1400px |
| --- | --- | --- | --- | --- | --- | --- |
| .container | 100% | 540px | 720px | 960px | 1140px | 1320px |
| .container-sm | 100% | 540px | 720px | 960px | 1140px | 1320px |
| .container-md | 100% | 100% | 720px | 960px | 1140px | 1320px |
| .container-lg | 100% | 100% | 100% | 960px | 1140px | 1320px |
| .container-xl | 100% | 100% | 100% | 100% | 1140px | 1320px |
| .container-xxl | 100% | 100% | 100% | 100% | 100% | 1320px |
| .container-fluid | 100% | 100% | 100% | 100% | 100% | 100% |

# **Creating Fluid Containers**

You can use the `.container-fluid` class to create a full width container. The width of the fluid container will always be 100% irrespective of the devices or screen sizes.

```html
<div class="container-fluid">
    <h1>This is a heading</h1>
    <p>This is a paragraph of text.</p>
</div>
```

# **Specify Responsive Breakpoints for Containers**

Since Bootstrap v4.4, you can also create containers that is 100% wide until the specified breakpoint is reached, after which max-width for each of the higher breakpoints will be applied.

For example, `.container-xl` will be 100% wide until the xl breakpoint is reached (i.e., viewport width ≥ 1200px), after which max-width for xl breakpoint is applied, which is 1140px.

```html
<div class="container-sm">100% wide until screen size less than 576px</div>
<div class="container-md">100% wide until screen size less than 768px</div>
<div class="container-lg">100% wide until screen size less than 992px</div>
<div class="container-xl">100% wide until screen size less than 1200px</div>
```

## Bootstrap responsive layout

```html
<div class="row">
            <div class="col-lg-4">
                <div class="demo-content">.col-lg-4     <img src="pfp - Copy.jpg" class="card-img-top" alt="...">
                </div>
            </div>
            <div class="col-lg-4">
                <div class="demo-content bg-alt">.col-lg-4 <img src="pfp - Copy.jpg" class="card-img-top" alt="..."></div>
            </div>
            <div class="col-lg-4">
                <div class="demo-content">.col-lg-4 <img src="pfp - Copy.jpg" class="card-img-top" alt="..."></div>

            </div>
        </div>>
```

 

### Bootstrap card

```html
<div class="card" style="width: 300px;">
    <img src="images/sample.svg" class="card-img-top" alt="...">
    <div class="card-body text-center">
        <h5 class="card-title">Alice Liddel</h5>
        <p class="card-text">Alice is a freelance web designer and developer based in London. She is specialized in HTML5, CSS3, JavaScript, Bootstrap, etc.</p>
        <a href="#" class="btn btn-primary">View Profile</a>
    </div>
</div>
```

# **Bootstrap Containers**

In this tutorial you will learn how to create containers with Bootstrap.

# **Creating Containers with Bootstrap**

Containers are the most basic layout element in Bootstrap and are required when using the grid system. Containers are basically used to wrap content with some padding. They are also used to align the content horizontally center on the page in case of fixed width layout.

Bootstrap provides three different types containers:

- `.container`, which has a max-width at each responsive breakpoint.
- `.container-fluid`, which has 100% width at all breakpoints.
- `.container-{breakpoint}`, which has 100% width until the specified breakpoint.

The table below illustrates how each container's max-width changes across each breakpoint.

For example, when using the `.container` class the actual width of the container will be 100% if the viewport width is <576px, 540px if the viewport width is ≥576px but <768px, 720px if the viewport width is ≥768px but <992px, 960px if the viewport width is ≥992px but <1200px, 1140px if the viewport width is ≥1200px but <1400px, and 1320px if the viewport width is ≥1400px.

Similarly, when you use the `.container-lg` class the actual width of the container will be 100% until the viewport width is <992px, 960px if the viewport width is ≥992px but <1200px, 1140px if the viewport width ≥1200px but <1400px, and 1320px if the viewport width is ≥1400px.

| Classes Bootstrap  Grid System | X-Small<576px | Small≥576px | Medium≥768px | Large≥992px | X-Large≥1200px | XX-Large≥1400px |
| --- | --- | --- | --- | --- | --- | --- |
| .container | 100% | 540px | 720px | 960px | 1140px | 1320px |
| .container-sm | 100% | 540px | 720px | 960px | 1140px | 1320px |
| .container-md | 100% | 100% | 720px | 960px | 1140px | 1320px |
| .container-lg | 100% | 100% | 100% | 960px | 1140px | 1320px |
| .container-xl | 100% | 100% | 100% | 100% | 1140px | 1320px |
| .container-xxl | 100% | 100% | 100% | 100% | 100% | 1320px |
| .container-fluid | 100% | 100% | 100% | 100% | 100% | 100% |

# **Bootstrap Responsive Layout**

In this tutorial you will learn how to create responsive websites with Bootstrap framework.

# **What is Responsive Web Design**

Responsive web design is a process of designing and building websites to provide better accessibility and optimal viewing experience to the user by optimizing it for different devices.

With the growing trend of smart phones and tablets, it has become almost unavoidable to ignore the optimization of sites for mobile devices. Responsive web design is a preferable alternative and an efficient way to target a wide range of devices with much less efforts.

Responsive layouts automatically adjust and adapts to any device screen size, whether it is a desktop, a laptop, a tablet, or a mobile phone. See the following Illustration.

![https://www.tutorialrepublic.com/lib/images/responsive-design-illustration.jpg](https://www.tutorialrepublic.com/lib/images/responsive-design-illustration.jpg)

---

# **Creating Responsive Layout with Bootstrap**

With the Bootstrap powerful mobile first [flexbox](https://www.tutorialrepublic.com/css-tutorial/css3-flexible-box-layouts.php) grid system creating the responsive and mobile friendly websites and applications has become much easier.

Bootstrap is responsive and mobile friendly from the start. Its [six tier grid classes](https://www.tutorialrepublic.com/twitter-bootstrap-tutorial/bootstrap-grid-system.php) provides better control over the layout as well as how it will be rendered on different types of devices like mobile phones, tablets, laptops and desktops, large screen devices, and so on.

The following example will create a responsive layout that is rendered as 4 column layout in extra-large devices (viewport ≥ 1200px), and 3 column layout in large devices (992px ≤ viewport < 1200px), whereas 2 column layout in medium devices (768px ≤ viewport < 992px), and 1 column layout in small and extra-small devices (viewport < 768px). Let's try it out and see how it works:

**Example**

```html
<!DOCTYPE html>
<html lang="en"><head><meta charset="utf-8"><meta name="viewport" content="width=device-width, initial-scale=1"><title>Bootstrap Responsive Layout Example</title><link rel="stylesheet" href="css/bootstrap.min.css"><script src="js/bootstrap.bundle.min.js"></script></head><body><nav class="navbar navbar-expand-lg navbar-dark bg-dark"><div class="container-fluid"><a href="#" class="navbar-brand">Tutorial Republic</a><button type="button" class="navbar-toggler" data-bs-
```

# **Bootstrap Buttons**

In this tutorial you will learn how to create and modify buttons with Bootstrap.

# **Creating Buttons with Bootstrap**

Buttons are the integral part of a website and application. They are used for various purposes like, submit or reset an [HTML form](https://www.tutorialrepublic.com/html-tutorial/html-forms.php), performing interactive actions such as showing or hiding something on a web page on click of the button, redirecting user to another page, and so on. Bootstrap provides a quick and easy way to create and customize the buttons.

# **Bootstrap Button Styles**

Different classes are available in Bootstrap for styling the buttons as well as to indicate the different states or semantic. Button styles can be applied to any element. However, it is applied normally to the `[<a>](https://www.tutorialrepublic.com/html-reference/html-a-tag.php)`, `[<input>](https://www.tutorialrepublic.com/html-reference/html-input-tag.php)`, and `[<button>](https://www.tutorialrepublic.com/html-reference/html-button-tag.php)` elements for the best rendering.

The following example will show you how to create different styles of buttons in Bootstrap:

**Example**

```markup
<button type="button" class="btn btn-primary">Primary</button><button type="button" class="btn btn-secondary">Secondary</button><button type="button" class="btn btn-success">Success</button><button type="button" class="btn btn-danger">Danger</button><button type="button" class="btn btn-warning">Warning</button><button type="button" class="btn btn-info">Info</button><button type="button" class="btn btn-dark">Dark</button><button type="button" class="btn btn-light">Light</button><button type="button" class="btn btn-link">Link</button>
```

— The output of the above example will look something like this:

![https://www.tutorialrepublic.com/lib/images/bootstrap-5/bootstrap-buttons.png](https://www.tutorialrepublic.com/lib/images/bootstrap-5/bootstrap-buttons.png)

---

# **Bootstrap Outline Buttons**

You can also create outline buttons by replacing the button modifier classes, like this:

**Example**

```markup
<button type="button" class="btn btn-outline-primary">Primary</button><button type="button" class="btn btn-outline-secondary">Secondary</button><button type="button" class="btn btn-outline-success">Success</button><button type="button" class="btn btn-outline-danger">Danger</button><button type="button" class="btn btn-outline-warning">Warning</button><button type="button" class="btn btn-outline-info">Info</button><button type="button" class="btn btn-outline-dark">Dark</button><button type="button" class="btn btn-outline-light">Light</button>
```

# **Changing the Sizes of Buttons**

Bootstrap gives you option further to scaling a button up or down.

To make buttons larger add an extra class `.btn-lg` to the buttons, like this:

**Example**

```markup
<button type="button" class="btn btn-primary btn-lg">Large button</button><button type="button" class="btn btn-secondary btn-lg">Large button</button>
```

— The output of the above example will look something like this:

![https://www.tutorialrepublic.com/lib/images/bootstrap-5/bootstrap-large-buttons.png](https://www.tutorialrepublic.com/lib/images/bootstrap-5/bootstrap-large-buttons.png)

Similarly, to make buttons smaller add an extra class `.btn-sm` to the buttons, like this:

**Example**

```markup
<button type="button" class="btn btn-primary btn-sm">Small button</button><button type="button" class="btn btn-secondary btn-sm">Small button</button>
```

— The output of the above example will look something like this:

![https://www.tutorialrepublic.com/lib/images/bootstrap-5/bootstrap-small-buttons.png](https://www.tutorialrepublic.com/lib/images/bootstrap-5/bootstrap-small-buttons.png)

You can also create full-width or block buttons (buttons that covers the full width of the parent elements) through using the Bootstrap's display and gap utility classes. These utilities offers much greater control over spacing, alignment, and responsive behaviors.

**Example**

```markup
<div class="d-grid gap-2"><button type="button" class="btn btn-primary">Block button</button><button type="button" class="btn btn-secondary">Block button</button></div>
```

— The output of the above example will look something like this:

![https://www.tutorialrepublic.com/lib/images/bootstrap-5/bootstrap-block-buttons.png](https://www.tutorialrepublic.com/lib/images/bootstrap-5/bootstrap-block-buttons.png)

You can also create responsive variation of these buttons using the `.d-{*breakpoint*}-block` classes.

In the following example buttons will be vertically stacked on small and extra small devices (i.e. viewport width <768px). From medium (`md`) breakpoint up `.d-md-block` replaces the `.d-grid` class, thus nullifying the `.gap-2` class. Let's try it out and see how it really works:

**Example**

```markup
<div class="d-grid gap-2 d-md-block"><button type="button" class="btn btn-primary">Button</button><button type="button" class="btn btn-secondary">Button</button></div>
```