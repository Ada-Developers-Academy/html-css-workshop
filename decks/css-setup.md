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

Open the Chrome Dev Tools on [adadev.org](adadev.org)

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

## Selecting by Class

Our rulesets apply to **all** of an element

What if we want to select **just one**?

We can add the `class` attribute to that element's HTML, then select by class!

<span class="small">Note: this is very different from a Ruby class!</span>

---

@snap[north-west span-57]

### HTML

```html
<ul>
  <li>Cherry</li>
  <li>Apple</li>
  <li class="favorite-fruit">Peach</li>
</ul>
```

Add the **class attribute** to the element you want to select

The value should be **kebab-case** (lowercase + dashes)

@snapend

@snap[north-east span-40 text-left]

### CSS

```css
.favorite-fruit {
  font-weight: bold;
  background-color: fuchsia;
}
```

<br>

Any selector that starts with a **period** will look for a class

@snapend

---

## Flexible Classes

You can add the same class to **multiple elements**

One element can have **multiple classes**, separated by spaces

```html zoom-15
<ul>
  <li class="stone-fruit">Cherry</li>
  <li>Apple</li>
  <li class="stone-fruit favorite">Peach</li>
</ul>
```

---

## Multiple Targets

A selector can have **multiple targets**

Targets are separated by **commas**

```css zoom-15
h1, h2, .important {
  background-color: aquamarine;
}
```

<span class="small">This will change the background color of all `<h1>` and `<h2>` elements **and** any element with the class `important`</span>

---

## Selector Practice

Use the `class` attribute to add the following pieces to your webpage:

- A paragraph where the text is both italic and bold
- A paragraph where the styles match those for `heading` elements

There are many other selectors beyond what we've covered today - feel free to explore!

---

@snap[north-west span-65]
## Rule Conflicts

What happens if **multiple rulesets** apply to the **same element**?

<br>

```html
<p class="target">
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

.target {
  background-color: blue;
}

p {
  color: olive;
}
```
@snapend

---

## Cascade

The way that different rules are applied to an element is called the **Cascade** (the C in CSS)

<span class="small">These are also sometimes called the rules of **precedence**</span>

- **Class selectors** have precedence over element selectors

- If the selector is the same, rules defined **later in the CSS file** have precedence

More complex selectors have more complex rules, but this is enough for us to get started

---

## Precedence Practice

Come up with **3 scenarios** where it's not obvious which CSS rule will apply

**Try them** on your web page and **observe** the results

Compare notes with your pod

---

## Review Questions

- What does CSS stand for?

- What are the parts of a CSS ruleset?

- What is the syntax for a CSS rule?

- How would you give all `<ul>` elements a blue background?

- How would you give one specific `<ul>` element a red background?

- Which of those two rules would have precedence?