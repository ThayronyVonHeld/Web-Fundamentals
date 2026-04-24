# 🌐 Lesson 7 — Semantics and Text Formatting in HTML

---

## 🧠 What is Semantics?

Semantics is related to the **meaning** of words, symbols, and elements.

👉 In HTML:

* It’s not just about **how something looks**
* It’s about **what it means**

---

## ⚠️ Old HTML vs Modern HTML

In HTML4, the focus was mostly on **appearance (form)**.

That’s why tags like these existed:

* `bgcolor="red"`
* `<center>`
* `<marquee>`

👉 These are now considered **obsolete**

---

## ✅ HTML5: Focus on Semantics

In HTML5, the focus changed:

* **HTML** → meaning (semantics)
* **CSS** → appearance (style)

👉 This is called **separation of concerns**

---

## 📍 Practical Example (Address)

### ❌ Old way (non-semantic):

```html id="exen01"
<p>I live at <u>123 Example Street - City</u></p>
```

👉 `<u>` only changes appearance (underline)

---

### ✅ Correct way (semantic):

```html id="exen02"
<p>I live at <address>123 Example Street - City</address></p>
```

👉 Now we are telling the browser:
**“this is an address”**

---

## ⚠️ Stay Updated

Some tags may become obsolete over time.

👉 Always:

* Keep learning
* Follow official documentation

---

## ✍️ Main Text Formatting

---

## 🔠 Bold

### ❌ Non-semantic:

```html id="ben01"
<b>Bold text</b>
```

👉 Only changes appearance

---

### ✅ Semantic:

```html id="ben02"
<strong>Important text</strong>
```

👉 Adds **meaning (importance)**

---

## ✒️ Italic / Emphasis

### ❌ Non-semantic:

```html id="ien01"
<i>Italic text</i>
```

---

### ✅ Semantic:

```html id="ien02"
<em>Emphasized text</em>
```

👉 Adds **emphasis to the content**

---

## 🧠 Key Takeaway

* `<b>` and `<i>` still work
* But they come from HTML4
* They do not add meaning

👉 Prefer:

* `<strong>`
* `<em>`

---

## 🖍️ Highlight (Mark Text)

You can highlight text using:

```html id="marken01"
<mark>Highlighted text</mark>
```

👉 Default:

* Yellow background
* Defined by the browser

---

## 🎨 Changing the Color (CSS)

HTML defines **meaning**, not style.

To change appearance, we use CSS.

---

### ✔️ Inline style (quick use):

```html id="marken02"
<mark style="background-color: lime;">Highlighted text</mark>
```

---

### ✔️ Internal style (better for reuse):

```html id="marken03"
<head>
  <style>
    mark {
      background-color: limegreen;
    }
  </style>
</head>
```

---

## ⚠️ Best Practice

* Quick changes → **inline CSS**
* Reusable styles → **internal or external CSS**

👉 For larger projects:

* Use external files (`style.css`)

---

## 🧠 Final Summary

Semantics in HTML means giving **meaning to content**, not just visual style. With the evolution to HTML5, old practices focused on appearance were replaced by semantic elements. Tags like `<strong>` and `<em>` should be preferred because they add meaning to the content. CSS is responsible for styling, keeping code organized and professional.

