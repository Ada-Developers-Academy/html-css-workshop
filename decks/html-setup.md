@snap[midpoint span-100]
# HTML Setup
@snapend

---

## Agenda

@snap[west span-50]

9:00  - Intro

<span style="color: #EF654A">9:30  - HTML Setup</span>

10:00  - **Break**

10:10  - Tags and Attributes

11:00 - **Break**

@snapend

@snap[east span-50 text-left]

11:10 - CSS

11:45 - Practice

12:15 - Wrap-up

12:30 - **Done!**

@snapend

---

## Learning Goals

By the end of this module, students will be able to...

- **Use** developer tools to inspect HTML

- **Set up** an HTML document and view it in the browser

- **Describe** the web development workflow

---

## What is HTML?

<span class="big">**Hypertext Markup Language**</span>

- **Hypertext**: text + links

- **Markup**: content + instructions

<br>

HTML defines the **structure** of a website

---

## Dev Tools

Open up Chrome and navigate to [adadev.org]()

Open the **developer tools** with `cmd + opt + i`

<ul class="small">
<li>Or right click (`ctrl` click) and click "inspect"</li>
<li>Think "i" for "inspect"</li>
</ul>
<br>

This allows you to see the page's HTML! Can you find...

- The Ada logo
- The "Testimonials" section
- The "Contact Us" link

---

## Making A Website

@snap[west span-60]

- Lots of instructions incoming!

- We're going to go **slow** - no one left behind!

- Check in with your **pod**

- Flag down a **volunteer**

- If there is a big technical problem, we can sort things out during the break
@snapend

@snap[east span-40]
![under construction](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d1/Vienna_Convention_road_sign_Ab-16-V1-LHT.svg/500px-Vienna_Convention_road_sign_Ab-16-V1-LHT.svg.png)
@snapend

---

## Overview

1. Open VS Code, create a new folder to work in

1. Create a file called `index.html` in that folder

1. Add basic HTML to the file

1. Open the file in the browser

---

@snap[north span-100]
### Open VS Code

`cmd + space` to open spotlight search

Type `vs code`, then press `enter` to launch

![](assets/images/setup/spotlight.png)
@snapend

---

@snap[north span-100]
### Create and Open a Folder
@snapend

@snap[west span-40]
`cmd + o` to open

Click `Documents` on the left, then the `New Folder` button at the top left

Type `ada-html-css-workshop`, then click `Create`

Click on the new folder, then click `Open`
@snapend

@snap[east span-60]
![](assets/images/setup/create-folder.png)
@snapend

---

@snap[north span-100]
### Create a File
@snapend

@snap[west span-40]
Open the `Explorer` side-bar

Click the `New File` button

Call the file `index.html`, then press `enter` to confirm
@snapend

@snap[east span-60]
![](assets/images/setup/create-file.png)
@snapend

---

@snap[north span-100]
### Insert Boilerplate
@snapend

@snap[west span-40]
Select the new `index.html` file

In the editor type `html` and a menu should pop up

Select `html:5`

Between `<body>` and `</body>` add

```html zoom-12
<h1>Hello, World!</h1>
```
@snapend

@snap[east span-60]
![](assets/images/setup/autocomplete.gif)
@snapend

---

@snap[north span-100]
### Open Finder
@snapend

@snap[west span-40]
`Ctrl + click` on the file

Select `Reveal in Finder`
@snapend

@snap[east span-60]
![](assets/images/setup/open-finder.png)
@snapend

---

@snap[north span-100]
### Open Chrome
@snapend

@snap[west span-40]
`Ctrl + click` on the file

Select `Open With` -> `Google Chrome`
@snapend

@snap[east span-60]
![](assets/images/setup/open-chrome.png)
@snapend

---

## Observe

1. What do you see in Chrome? Is it what you expected?

1. Switch to VS Code and **change** "World" to your name

1. **Save** the file (`cmd+s`)

1. Switch to Chrome and **refresh** the page (`cmd+r`)

1. What do you see? Is it what you expected?

---


@snap[west span-55]

## Workflow

<!-- https://www.draw.io/#G1ELMm8QyMA8CIdgTxyifjE5ZiB6As2aXh -->
![webdev workflow](assets/images/HTML-developer-flow.png)
@snapend

@snap[east span-45]
How is this similar to working in Ruby?
@snapend

---

## Dev Tools on Our Site

Open up the Chrome Dev Tools on your page

What do you see?

Is it different than the HTML you typed?

---

## Review Questions

- What does HTML stand for?

- How do you open the Chrome Dev Tools?

- After you make changes to a `.html` file with VS Code, what are the steps to see the change in the browser?
