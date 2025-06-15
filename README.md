# Team Website Project

Welcome to your team's website project! This repository contains a set of starter files that you will work on together to transform into a live website.

I've included a "Pizza Shop" example to get you started, but you should choose your own topic. The goal is for you to explore how HTML, CSS, and GitHub work together as a team. **You will edit the content of the `.html` files and are encouraged to change the look and feel in the `styles.css` file to make the project your own.**

---

## 1. Assessment Details

Before you begin, everyone in your team should read the requirements for the Assessment 2 in the Google Classroom.

---

## 2. Your Starter Kit

Your project begins with the following files. Take a moment to look through them.

* `index.html` — The main "Home" page of a pizza shop, demonstrating a basic layout with navigation and an image. You can edit this (and any files) for your team topic.
* `faq.html` — A sample "FAQ" page showing how to use lists and links.
* `my-page-template.html` — A blank but structured page. **Duplicate this** to create new pages for your site (e.g., `about.html`, `contact.html`).
* `base.html` — A minimal scaffold with **only** the essential HTML tags (`<header>`, `<nav>`, `<footer>`). Use this if you want to build a page completely from scratch.
* `styles.css` — The main stylesheet for the project. It's well-commented to help you understand how it works. **You should edit this file freely—change colours, fonts, spacing, and anything else to create a unique design.**
* `alt-styles.css` — An optional, alternate theme. You can swap this in to see how quickly you can change the look of your site.
* `pizza.jpg` — An example image used on the `index.html` page. You should replace this with your own images.

---

## 3. How to Start Editing

Follow these steps to open the project in the web-based editor. No installation is needed!

1.  **Accept the Invitation:** I have added you to this project. Check your email for an invitation from GitHub and click the link to **Accept**.
2.  **Open the Web Editor:** Once you are on the main page of this repository, simply press the **`.`** (full stop) key on your keyboard.
3.  **Explore:** A full VS Code editor will load in your browser. Click on any file in the list on the left to view its code.

If you choose you can download the GitHub app and VS Code app instead of using the web versions. We'll focus on the web versions here. 

---

## 4. Making Your First Change

Let's try a simple edit to see how the workflow feels.

1.  **Edit the Title:** Open the `index.html` file. Find the `<title>` tag and the `<h1>` tag and change their text to match your team's chosen topic.
2.  **Save Your Work:** In GitHub, you "commit" your changes. This is like a permanent, named save that you share with your team.
    * Click the **Source Control** icon on the left-side menu (it looks like three branching lines).
    * In the "Message" box, type a clear, short summary of your change (e.g., "Update homepage title").
    * Click the **"Commit & Push"** button to save your work to the cloud.

---

## 5. Adding a New Page

Here’s how to add a new page to your site using the provided template.

1.  **Duplicate the Template:** In the file explorer on the left, right-click on `my-page-template.html` and choose **"Duplicate"**.
2.  **Rename It:** Give your new file a descriptive name, like `gallery.html` or `contact.html`.
3.  **Add Your Content:** Edit your new file. Change the `<h1>` and fill the page with your own text, images, and content.
4.  **Link to It:** To make your new page accessible, you need to add a link to it in the navigation bar. Open `index.html` (and any other pages you have) and add a new list item inside the `<nav>` section:
    ```html
    <li><a href="gallery.html">Gallery</a></li>
    ```
5.  **Commit Your Changes:** Go to the Source Control panel, write a clear message (e.g., "Add Gallery page and navigation link"), and click **"Commit & Push"**.

---

## 6. Exploring CSS Themes

You can dramatically change your site's appearance just by swapping the stylesheet.

* **To use the alternate theme:** Open `index.html` and find the `<link>` tag in the `<head>` section. Comment out the original stylesheet and uncomment the alternate one, like this:
    ```html
    <link rel="stylesheet" href="alt-styles.css">
    ```
* Save the file and commit the change to see the new look. You can even create your own `dark-mode.css` or `retro.css` and experiment!

---

## 7. Tips for Great Teamwork

* **Communicate:** Before you start editing a file (especially `styles.css`), let your teammates know in your group chat. This prevents two people from changing the same thing at the same time.
* **Commit Often:** It's better to save 5 small changes with clear messages than one giant, confusing change. This creates a clear history of who did what.
* **Pull Before You Push:** If you're working on the desktop version of VS Code, always "pull" (download) the latest changes to your computer before you start working. In the web editor, a simple page refresh usually is enough. Then commit your changes ("push"/upload to the cloud). 

Have fun exploring and turning these starter files into your own website
```
