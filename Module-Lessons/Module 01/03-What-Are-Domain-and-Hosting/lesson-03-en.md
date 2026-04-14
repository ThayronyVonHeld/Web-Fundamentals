# 🌐 Lesson 3 — What Are Domain and Hosting?

---

## ❓ How can other people access my website?

Let’s recall an important concept from the previous lesson:

When you access a website, you are connecting to a **server**, which has an:

👉 **IP Address (Internet Protocol)**

### Example:

* Server → `3.244.112.47`
* Your device → `172.23.41.49`

---

## 🔎 Domains and DNS (Review)

Memorizing IP addresses would be very difficult, so we use domain names like:

* `instagram.com`

This is possible thanks to the DNS.

### How it works:

1. You type a domain
2. Your device queries a DNS server
3. DNS returns the corresponding IP address
4. You are connected to the correct server

---

## ⚠️ Problem: My website is on my computer

If your website is only stored on your personal computer:

👉 **Other people cannot access it**

Why?

* Your computer is not a public server
* It is not exposed to the internet
* There is no domain linked to it
* DNS cannot find it

---

## 🌍 Solution: Hosting + Domain

To make your website accessible, you need two things:

---

### 🏠 Hosting

This is where your website is stored.

* Storage space for files
* Memory and processing resources
* A server connected to the internet

👉 It can be:

* Paid (most common)
* Free (with limitations)

---

### 🌐 Domain

This is your website’s name on the internet.

Example:

* `github.io`

📌 Characteristics:

* Must be **unique**
* Usually **paid annually**
* Has different types (TLDs)

---

## 🔗 Practical Example

Let’s analyze:

👉 `gustavoguanabara.github.io`

* `gustavoguanabara` → subdomain
* `github.io` → domain
* `.io` → TLD

---

## 🧩 Structure of a URL

A URL (Uniform Resource Locator) is the full address of a resource on the internet.

### Example:

👉 `www.github.com/ThayronyVonHeld`

Breaking it down:

* `www` → subdomain
* `github.com` → domain
* `.com` → TLD
* `/ThayronyVonHeld` → path

---

## 🌐 Types of TLD

TLD (Top-Level Domain) is the last part of a domain.

### Main types:

* **gTLD (generic)**

  * `.com`, `.org`, `.net`, `.io`

* **ccTLD (country code)**

  * `.br` (Brazil)
  * `.es` (Spain)

---

## 🔐 Another Full Example

👉 `https://gustavoguanabara.github.io`

Let’s identify:

* `https://` → protocol
* `gustavoguanabara` → subdomain
* `github.io` → domain
* `.io` → TLD

👉 All of this together forms the **complete URL**

---

## 🧠 Final Summary

For a website to be accessible on the internet, it must be hosted on a server and have a domain name. The domain acts as an easy-to-remember address, while hosting stores the website’s files. The URL is the complete address used to access the resource, and DNS is responsible for translating the domain into an IP address.

