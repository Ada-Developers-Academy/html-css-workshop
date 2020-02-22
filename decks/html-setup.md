# HTML Setup

---

## Agenda

9:00 - Intro

<span style="color: #EF654A">9:20 - HTML Setup</span>

**9:40 - Break**

9:50 - Tags and Attributes

10:10 - CSS Setup

**10:30 - Break**

10:40 - Styling

11:00 - Selectors

11:20 - Project Time **+ Break**

12:10 - Deployment

**12:30 - Done!**

---

## Learning Goals

By the end of this module, students will be able to...

- Set up an HTML document and view it in the browser
- Use developer tools to inspect HTML
- Differentiate between the `<head>` and `<body>` of an HTML document
- Define key terms related to HTML

---

## What is HTML?

---

## Dev Tools

on a live website

---

## Making our own site

---

## Instructions: file setup

- make a folder for the workshop
- make a folder for the section
- open the folder in VS Code
- make a file

---

## Instructions: add HTML boilerplate + h1 element

---

## Instructions: open file in chrome

- Make a change and refresh

---


@snap[west span-55]

## Workflow

<!-- https://www.draw.io/#G1ELMm8QyMA8CIdgTxyifjE5ZiB6As2aXh -->
![webdev workflow](assets/images/HTML-developer-flow.png)
@snapend

@snap[east span-45]
Question: How is this similar to working in Ruby?
@snapend

---

## Instructions: dev tools on our site

---

## HTML Vocab - Elements

<!-- https://www.draw.io/#G1flliSXhehhQJ2Et3rkxicG4bTQzxKeMO -->

![html element vocab](assets/images/HTML-vocab-element.png)

Element = Open Tag + Content + Close Tag

Open and close tags must match (`<h1>` to `</h1>`, `<p>` to `</p>`)

Content can be anything - even other elements!

---

## HTML Vocab - Tags

<!-- https://www.draw.io/#G1flliSXhehhQJ2Et3rkxicG4bTQzxKeMO -->

![html tag vocab](assets/images/HTML-vocab-tag.png)

The element's **name** is one lowercase word

Some elements have **attributes** in the open tag

Attributes usually need a **value** in quotes

---

## HTML Vocab - Nesting

@snap[east span-40]

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

@snap[west span-57]
We can **nest** elements inside each other

- The outer element is the **parent**

- Inner elements are **children**

- Children of the same parent are **siblings**

@snapend

---

## HTML Vocab - Self-Closing Tags

Some elements are just one tag, no content and no close tag

```html zoom-15
<img src="assets/images/logo.png">
```

We call these **self-closing** tags

Question: can a self-closing tag have children?

---

## `<head>` and `<body>`

---

## Comments

---

## Comprehension Questions
