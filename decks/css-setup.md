@snap[midpoint span-100]

# CSS Setup

@snapend

---

# TODO AGENDA

---

## Learning Goals

By the end of this module, students will be able to...

- Set up a CSS document and attach it to a web page
- Use CSS to change the appearance of a web page
- Select elements by tag name
- Use classes to select specific elements
- Use developer tools to inspect CSS
- Define key terms related to CSS

---

## What is CSS?

<span class="big">**Cascading Style Sheets**</span>

- **Cascading**: how the browser chooses which rule applies (more on this later)

- **Style**: how does the page look

- **Sheets**: separate files

<br>

CSS defines the **appearance** of a website

---

## CSS Dev Tools

Open the Chrome Dev Tools on adadev.org

Select an element and look at the bottom panel. This shows the **styles** that are affecting the element

What do you notice?

---

## Linking the Stylesheet

<ol>
<li>
Create a file in the same directory called `index.css`
</li>
<li>
Add the following code to the CSS file:
```css zoom-10
body {
  background-color: orange;
}
```
</li>
<li>
In `index.html`, add the following self-closing tag inside the `<head>` element:
```html zoom-10
<link rel="stylesheet" href="index.css" />
```
</li>
<li>
Save both files and refresh the page in Chrome. You should see an orange background!
</li>
</ol>

---

## Vocab: Ruleset

![CSS vocab](assets/images/CSS-vocab.png)

**Ruleset** = selector + rule(s)

**Rule** = property + value

What Ruby data structure does this remind you of?

---

## Selecting by Element

---

## Selecting by Class

---

## Comprehension Questions