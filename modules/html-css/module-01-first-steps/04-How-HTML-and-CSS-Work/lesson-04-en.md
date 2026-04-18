# 🌐 Lesson 4 — How HTML and CSS Work

---

## ❗ Are HTML and CSS programming languages?

There is a very common misconception:

👉 “I program in HTML and CSS”

This statement is **not correct**.

* HTML and CSS are **not programming languages**
* They are **markup and styling languages**

📌 The correct way to say it is:
👉 **“I develop with HTML and CSS”**

---

## 🧾 What is HTML?

HTML stands for:

* **HyperText** → text with clickable links
* **Markup Language** → a language used to structure content

👉 HTML is responsible for **content structure**

### Examples of content:

* Text
* Images
* Videos
* Lists
* Tables

---

## 🎨 What is CSS?

CSS stands for:

* **Cascading Style Sheets**

👉 CSS is responsible for the **visual design** of a website

### Examples:

* Colors
* Sizes
* Fonts
* Spacing
* Layout/positioning

---

## 🧠 What about JavaScript?

There is a third essential component:

👉 JavaScript

* Responsible for **interactivity**
* Acts as the “brain” of the website

### Examples:

* Interactive menus
* Animations
* Form validation
* Pop-ups

---

## ⚙️ The Web Development Triad

* **HTML** → Structure (content)
* **CSS** → Appearance (design)
* **JavaScript** → Behavior (interaction)

👉 These three technologies are the foundation of modern web development.

---

## 🏗️ How does HTML work?

HTML is based on **tags (markup elements)**.

### Tag structure:

* Opening tag → `<h1>`
* Content → `Title`
* Closing tag → `</h1>`

### Example:

```html
<h1>Example title</h1>
<p>Example paragraph</p>
```

---

## 🧩 Self-closing (void) tags

Some tags do not require a closing tag.

### Example:

```html
<img src="photo.png" alt="Example image">
```

### Explanation:

* `src` → image source (path)
* `alt` → alternative text (accessibility)

---

## 🎨 How does CSS work?

CSS works with **selectors and declarations**.

### Example:

```css
h1 {
  font-family: Arial;
  font-size: 20pt;
  color: blue;
}
```

### Structure:

* **Selector** → `h1`
* **Declarations** → inside `{}`
* **Property** → `color`
* **Value** → `blue`

👉 Each line is a pair: **property + value**

---

## 📄 Basic HTML document structure

This structure is required:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>

<body>
  <h1>Hello, World!</h1>
</body>
</html>
```

---

## 🧠 Understanding the structure

* `<!DOCTYPE html>` → defines HTML5
* `<html lang="en">` → page language
* `<head>` → configurations and metadata
* `<body>` → visible content

### Important meta tags:

* `<meta charset="UTF-8">`
  👉 Supports special characters (accents, symbols)

* `<meta name="viewport">`
  👉 Enables responsive design

* `<title>`
  👉 Browser tab title

---

## 🌐 How do HTML and CSS work in practice?

Recalling previous lessons:

1. You type a URL
2. The DNS returns the IP
3. Your browser connects to the server
4. The server sends HTML and CSS files
5. The browser interprets these files

👉 Result:
The browser **renders** the code into a visual interface

---

## 🧠 Final Summary

HTML and CSS are the foundation of web development. HTML defines the structure and content, while CSS controls the appearance. Together with JavaScript, they form the essential toolkit for building modern websites. When you access a site, your browser fetches these files from a server, interprets the code, and displays the final visual result on your screen.

---
