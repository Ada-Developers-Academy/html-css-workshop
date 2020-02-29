@snap[midpoint span-100]
# HTML Setup
@snapend

---

## Agenda

@snap[west span-50]

9:00  - Intro

<span style="color: #EF654A">9:20  - HTML Setup</span>

9:40  - **Break**

9:50  - Tags and Attributes

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

- Use developer tools to inspect HTML
- Set up an HTML document and view it in the browser
- Describe the web development workflow

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

## Instructions: Files

1. Open the **Finder** app

1. Select the **"Documents"** folder on the left

1. Control-click to open the menu and click **"New Folder"**

1. Call the folder "ada-html-css-workshop"

1. Open the **VS Code** app

1. Choose File -> Open (`cmd+o`), select "Documents" on the left, **select the new folder** and click "Open"

---

## Instructions: Code

1. Hit `cmd+shift+e` to open the **"Explorer" pane**

1. Click the **"New File"** button to add a file

1. Call the file `index.html` and hit enter to confirm

1. In the file, **type "`html`"** and VS Code should show a menu

1. Use the arrow keys to select `html:5` and hit `tab`

1. Between `<body>` and `</body>`, add this line:

```html zoom-15
<h1>Hello, World!</h1>
```

---

## Instructions: Observe

1. Open Finder and **navigate to the folder** we created earlier under Documents

1. Control-click on `index.html`, then select

    "Open With" -> **"Google Chrome"**

1. What do you see? Is it what you expected?

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
