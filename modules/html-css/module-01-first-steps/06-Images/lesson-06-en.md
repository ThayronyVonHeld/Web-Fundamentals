# 🌐 Lesson 6 — Images and Favicon

---

## ⚠️ Copyright and Usage Rights

A very important topic in web development is the use of third-party content.

👉 Images, videos, and other assets **may be protected by copyright**

Improper use can lead to:

* Legal issues
* Content removal
* Penalties

---

## ✅ Solution: Use Free Images

A safe approach is to use **free/copyright-free images**.

Example platform:

* Unsplash

📌 Note:
Even on free platforms, always check:

* License terms
* Attribution requirements

---

## 🖼️ Image Formats for the Web

The most common formats are:

* **JPEG/JPG**
* **PNG**
* **GIF**
* **SVG**
* **TIFF** (rarely used on the web due to size)

---

## 🤔 Which format should you use?

👉 It depends on your use case:

* **JPEG**

  * Smaller file size
  * Ideal for photos
  * Uses compression (some quality loss)

* **PNG**

  * Higher quality
  * Supports transparency
  * Larger files than JPEG

* **GIF**

  * Supports animations
  * Limited quality

* **SVG**

  * Vector-based (no quality loss when scaling)
  * Ideal for icons and logos

---

## ⚠️ Essential Tip

👉 **Avoid heavy images!**

Large images:

* Slow down your website
* Hurt user experience
* Impact SEO

---

## 📏 Image Size and Resolution

If an image is too large (e.g., 3840×2160):

👉 Solutions:

* Resize the image
* Compress the file
* Choose the appropriate format

Smaller file sizes (without significant quality loss) improve performance.

---

## 🧩 How to Add Images in HTML

Use the tag:

```html id="imgen01"
<img src="" alt="">
```

### Attributes:

* `src` → image source (path or URL)
* `alt` → alternative text (accessibility + SEO)

---

## 📁 Usage Examples

### Same folder:

```html id="imgen02"
<img src="logo-html.png" alt="HTML Logo">
```

### Different folder:

```html id="imgen03"
<img src="assets/logo-css.png" alt="CSS Logo">
```

### From the web:

```html id="imgen04"
<img src="https://upload.wikimedia.org/wikipedia/commons/d/d4/JavaScript-shield.svg" alt="JavaScript Logo">
```

📌 Important:
Make sure the path (relative or absolute) is **correct**.

---

## 🎨 Adjusting Image Size

By default, images are displayed in their original size.

You can:

* Edit them using image tools
* Or use CSS (recommended, covered later)

---

## ⭐ What is a Favicon?

A favicon is the small icon displayed in the browser tab.

Example:

* YouTube tab → name + icon

---

## 🧩 How to Add a Favicon

### 1. Choose an icon

Useful platforms:

* IconArchive
* Favicon.io
* Favicon.cc

👉 Recommended format:

* `.ico` (better compatibility)

---

### 2. Add it to your HTML

Inside the `<head>` tag:

```html id="faven01"
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
```

---

## 🌐 How does this work in practice?

Recapping previous lessons:

1. You access a website
2. The server sends HTML + CSS + images
3. The browser loads these files
4. Images are rendered on the screen

👉 In other words:
Images are part of the **resources loaded by the browser**

---

## 🧠 Final Summary

In web development, properly using images is essential for both performance and legal compliance. Developers must choose the right formats, optimize file sizes, and respect copyright rules. Additionally, elements like favicons enhance a website’s identity and user experience.
