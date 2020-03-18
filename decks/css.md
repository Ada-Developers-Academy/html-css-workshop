@snap[midpoint span-100]

# CSS

@snapend

---

## Agenda

@snap[west span-50]

9:00  - Intro

9:30  - HTML Setup

10:00  - **Break**

10:10  - Tags and Attributes

11:00 - **Break**

@snapend

@snap[east span-50 text-left]

<span style="color: #EF654A">11:10 - CSS</span>

11:45 - Practice

12:15 - Wrap-up

12:30 - **Done!**

@snapend

---

## Learning Goals

By the end of this module, students will be able to...

- **Set up** a CSS document and attach it to a web page

- **Describe** the syntax of a CSS ruleset

- **Use** element and class selectors in CSS

- **Debug** CSS using the Chrome Developer Tools

- **Define** key terms related to CSS: rule, ruleset, selector, class, cascade, precedence

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

Open the Chrome Dev Tools on [adadev.org](adadev.org)

Select an element and look at the bottom panel. This shows the **styles** that are affecting the element

What do you notice?

---

## Linking the Stylesheet

<ol>
<li>
Create a file in the same folder called `index.css`
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

The **selector** tells the browser what elements are covered by the rule

**All** matching elements will have their styles changed

```css zoom-15
img {
  width: 300px;
}
```

<span class="small">This will make **all images** have a width of 300 pixels</span>

---

## CSS Practice

Add the following styles to your web page:

- All `<h1>` tags use the font "Times New Roman"

- All `<li>` tags have a solid black border 1 pixel wide

- All `<p>` tags have centered text of size 28 pixels

---

## Debugging CSS

What happened when you made a mistake?

- Select an element that doesn't exist

- Spell a property or value wrong

- Forget a semicolon

How can you figure out what went wrong?

---

## CSS Comments

The browser ignores anything between `/*` and `*/`

These are called comments, just like in Ruby

In VS Code, `cmd+/` turns the current line into a comment

---

## Multiple Targets

A selector can have **multiple targets**

Targets are separated by **commas**

```css zoom-15
h1, a {
  background-color: aquamarine;
}
```

<span class="small">This will change the background color of all `<h1>` and `<a>` elements</span>

---

@snap[north-west span-65]
## Rule Conflicts

What happens if **multiple rulesets** apply to the **same element**?

Make a **prediction**, then try it out!

<br>

```html
<p>
  This is a paragraph
</p>
```
@snapend

@snap[east span-35]
```css
p {
  background-color: red;
  color: navy;
}

p {
  color: olive;
}
```
@snapend

---

## Review Questions

- What does CSS stand for?

- What are the parts of a CSS ruleset?

- What is the syntax for a CSS rule?

- How would you give all `<ul>` elements a blue background?
