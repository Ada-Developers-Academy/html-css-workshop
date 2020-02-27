@snap[midpoint span-100]
# Tags and Attributes
@snapend

---

# TODO AGENDA

---

## `<head>` and `<body>`

`<body>` contains everything that appears on the page 

What does `<head>` contain?

Try changing the `<title>` tag - what happens?

---

## Vocab - Elements

<!-- https://www.draw.io/#G1flliSXhehhQJ2Et3rkxicG4bTQzxKeMO -->

![html element vocab](assets/images/HTML-vocab-element.png)

Element = open tag + content + close tag

Open and close tags **must match** (e.g. `<h1>` to `</h1>`)

Content can be anything - even other elements!

---

## Vocab - Tags

<!-- https://www.draw.io/#G1flliSXhehhQJ2Et3rkxicG4bTQzxKeMO -->

![html tag vocab](assets/images/HTML-vocab-tag.png)

The element's **name** is one lowercase word

Some elements have **attributes** in the open tag

Attributes usually need a **value** in quotes

---

## Vocab - Nesting

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

## Vocab - Self-Closing

Some elements have no content and no close tag

```html zoom-15
<img src="images/ada-logo.png">
```

We call these **self-closing** tags

**Question:** can a self-closing tag have children?

---

## Comments

The browser ignores anything between `<!--` and `-->`

These are called comments, just like in Ruby

In VS Code, `cmd+/` turns the current line into a comment

---

## Tags Jigsaw

Pods of 4

2 minutes: **Intro**

5 minutes: **Research** your tags

8 minutes: **Teach** your pod (2 minutes each)

5 minutes: **Practice**

---

@snap[north-west span-50]

### Tags

1. Links and paragraphs<div class="indent">`<a>`, `<p>`</div>
1. Lists<div class="indent">`<ul>`, `<ol>`, `<li>`</div>
1. Images<div class="indent">`<img>`</div>
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

Use these elements to create a page. It should include:

- `<header>` and `<main>` sections
- Several paragraphs (don't spend too much time writing)
- At least one list
- At least one image
- At least one link

Idea: make a bio for yourself
