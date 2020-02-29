@snap[midpoint span-100]

# Deployment

@snapend

---

# TODO AGENDA

---

## Learning Goals

By the end of this module, students will be able to...

- **Define** deployment and related key terms: client, server, host, hosting service

- **Describe** different approaches to deployment

- **Use** GitHub Pages to deploy a web site

---

## Why Deploy?

Right now your web site only exists on your computer

If you want to share it with others, you'll need to put it "on the internet" somehow

We call the act of sharing our code on the public internet **deployment**

---

## Clients and Servers

Our website code will live on some computer that's connected to the internet

<span class="small">We call the computer where the code lives a **server**, and say that it **hosts** our code</span>

Other people can tell their computers to ask our computer for the code so they can run it

<span class="small">The computer that wants the code is called a **client**</span>

<span class="small">You use a web browser like Chrome to ask for code from the server</span>

---

## Clients and Servers

<!-- https://www.draw.io/#G1NEFo2BS7eG_cCnXjqzHRgy5h8NLLa1Hg -->

@snap[midpoint span-100]
![clients and servers](assets/images/client-server.png)
@snapend

---

## Ways to Deploy

We could use our own computer as the server (**self-hosting**)
<ul class="small">
<li>How do we get a web address?</li>
<li>Do we need to worry about security?</li>
<li>What if we want to turn our computer off?</li>
</ul>

<br>

Or we could use a **hosting service** to do most of the work for us

---

@snap[north-west span-65]
## GitHub Pages

Hosting service provided by GitHub

<span class="small">GitHub is a tool for tracking and sharing code, used both at Ada and in industry</span>

Simple but powerful

Perfect for our needs today
@snapend

@snap[east span-35]
![github logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
@snapend

---

## Deploying A Website

@snap[west span-60]

- Lots of instructions incoming!

- We're going to go **slow** - no one left behind!

- Check in with your **pod**

- Flag down a **volunteer**

- If there is a big technical problem, we can sort things out after class
@snapend

@snap[east span-40]
![under construction](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d1/Vienna_Convention_road_sign_Ab-16-V1-LHT.svg/500px-Vienna_Convention_road_sign_Ab-16-V1-LHT.svg.png)
@snapend

---

@snap[north span-100]
### Create a new repository (repo)
@snapend

@snap[midpoint span-70]
![create repo button](assets/images/deployment-new-repo-1.png)
@snapend

---


@snap[north span-70]
### Fill in the repo settings

![create repo page](assets/images/deployment-new-repo-2.png)
@snapend

---

@snap[north span-100]
### Upload your files

![upload button](assets/images/deployment-upload-1.png)
@snapend

---

@snap[north span-100]
### Choose files directly

![upload page](assets/images/deployment-upload-2.png)
@snapend

---

@snap[north span-100]
### Select both the HTML and CSS files
@snapend

@snap[midpoint span-80]
![upload select files](assets/images/deployment-upload-3.png)

Make sure to upload any images or additional pages
@snapend

---

@snap[north span-100]
### Commit changes

![upload commit](assets/images/deployment-upload-4.png)
@snapend

---

@snap[north span-100]
### Go to the Settings tab

![settings button](assets/images/deployment-settings-button.png)
@snapend

---

@snap[north span-100]
### Enable GitHub Pages

![gh pages settings](assets/images/deployment-gh-pages-settings.png)
@snapend

---

## ✅ Deployed

Your site is now live on the internet!

`https://<username>.github.io/<repo-name>`

<span class="small">Don't type out the angle brackets, those mean "fill this in"<span>

<br>

Hint: There's a link on the GitHub Pages section of the Settings page