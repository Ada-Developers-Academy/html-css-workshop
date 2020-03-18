@snap[midpoint span-100]
# Tags and Attributes
@snapend

---

## Agenda

@snap[west span-50]

9:00  - Intro

9:20  - HTML Setup

9:40  - **Break**

<span style="color: #EF654A">9:50  - Tags and Attributes</span>

10:30 - **Break**

@snapend

@snap[east span-50 text-left]

10:40 - CSS

11:20 - Practice

12:00 - Practice Wrap-up

12:10 - Deployment

12:30 - **Done!**

@snapend

---

## Learning Goals

By the end of this module, students will be able to...

- **Differentiate** between the `<head>` and `<body>` of an HTML document

- **Define** key terms related to HTML: element, tag, attribute, value, nesting, self-closing

- **Use** common HTML elements to structure the content of a web page

---

## `<head>` and `<body>`

`<body>` contains everything that appears on the page 

What does `<head>` contain?

Try changing the `<title>` tag - what happens?

---

## Syntax - Elements

<!-- https://www.draw.io/#G1flliSXhehhQJ2Et3rkxicG4bTQzxKeMO -->

![html element vocab](assets/images/HTML-vocab-element.png)

Element = open tag + content + close tag

Open and close tags **must match** (e.g. `<h1>` to `</h1>`)

Content can be anything - even other elements!

---

## Syntax - Tags

<!-- https://www.draw.io/#G1flliSXhehhQJ2Et3rkxicG4bTQzxKeMO -->

![html tag vocab](assets/images/HTML-vocab-tag.png)

The element's **name** is one lowercase word

Some elements have **attributes** in the open tag

Attributes usually need a **value** in quotes

---

## Syntax - Nesting

@snap[east span-50]

```html zoom-15
<article>
  <h1>Instructions</h1>
  <p>
    Please fill out...
  </p>
</article>
```

@[1, 6]
@[2]
@[2-5]

@snapend

@snap[west span-50]
We can **nest** elements inside each other

- The outer element is the **parent**

- Inner elements are **children**

- Children of the same parent are **siblings**

@snapend

---

## Syntax - Self-Closing

Some elements have no content and no close tag

```html zoom-15
<img src="images/ada-logo.png">
```

We call these **self-closing** tags

**Question:** can a self-closing tag have children?

---

## HTML Comments

The browser ignores anything between `<!--` and `-->`

These are called comments, just like in Ruby

In VS Code, `cmd+/` turns the current line into a comment

---

## Review Questions

- What are the parts of an element?

- What are the parts of a tag?

- What is the syntax for setting an attribute?

- How is a self-closing element different?

- What are the `<head>` and `<body>` tags for?

---

## Tags Jigsaw

Pods of 4

2 minutes: **Intro**

8 minutes: **Research** your tags

10 minutes: **Teach** your pod (2 minutes each)

---

@snap[north-west span-50]

### Tags

1. Links and images<div class="indent">`<a>`, `<img>`</div>
1. Lists<div class="indent">`<ul>`, `<ol>`, `<li>`</div>
1. Paragraphs, strong and emphasis<div class="indent">`<p>`, `<strong>`, `<em>`</div>
1. Sectioning elements<div class="indent">`<header>`, `<footer>`, `<main>`, `<nav>`</div>

@snapend

@snap[north-east span-50 text-left]

### Questions

What is it **for**?

How can you remember the **tag name**?

How does it **look** on the page?

What **attributes** (if any) does it take?

@snapend

---

## Practice

Use these elements to create a web page. It should include:

- `<header>` and `<main>` sections
- Several paragraphs (don't spend too much time writing)
- At least one list
- At least one image
- At least one link

Idea: turn your favorite recipe into a web page
