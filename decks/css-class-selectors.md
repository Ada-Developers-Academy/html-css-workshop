
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

## Selector Practice

Use the `class` attribute to add the following pieces to your webpage:

- A paragraph where the text is both italic and bold

- A paragraph where the styles match those for `heading` elements

There are many other selectors beyond what we've covered today - feel free to explore!

---

## Cascade

The way that different rules are applied to an element is called the **Cascade** (the C in CSS)

<span class="small">These are also sometimes called the **rules of precedence**</span>

- **Class selectors** have precedence over element selectors

- If the selector is the same, rules defined **later in the CSS file** have precedence

More complex selectors have more complex rules, but this is enough for us to get started

---

## Precedence Practice

Come up with **3 scenarios** where it's not obvious which CSS rule will apply

**Try them** on your web page and **observe** the results

Compare notes with your pod
