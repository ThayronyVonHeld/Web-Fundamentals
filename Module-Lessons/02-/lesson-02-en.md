# 🌐 Lesson 2 — How Does the Internet Work?

---

## 💻 How Do Computers Represent Data?

Computers are electronic machines that operate using only two signals:

👉 **0 and 1** (binary system)

These are called:

* **Bits (binary digits)** → the smallest unit of data

A single bit (0 or 1) is not enough to represent meaningful information.
So, computing defines a minimum unit:

👉 **1 Byte = 8 bits**

Example:

* `01000001` → represents the letter **"A"** in UTF-8

When you press a key (like “A”), your computer interprets it as a sequence of bits grouped into bytes.

---

## 📦 Byte Multiples

Just like measurement units (kg, g, mg), computing uses multiples of bytes:

* **1024 Bytes** = 1 Kilobyte (KB)
* **1024 KB** = 1 Megabyte (MB)
* **1024 MB** = 1 Gigabyte (GB)
* **1024 GB** = 1 Terabyte (TB)
* **1024 TB** = 1 Petabyte (PB)

📌 Important:

* Computers use **base 2**, not base 10
* That’s why 2¹⁰ = 1024

---

## ⚠️ MB vs Mb

There is an important difference:

* **MB (Megabytes)** → storage
* **Mb (Megabits)** → data transmission

👉 Example:
Your internet plan might be **500 Mb (megabits per second)**

---

## 🌐 How Do We Connect to the Internet?

To access the internet, you act as a **client**, requesting services (like websites).

### Connection paths:

* **Computer:**
  PC → Modem → Internet

* **Mobile:**
  Phone → Antenna → Internet

You need an Internet Service Provider (ISP) to make this connection possible.

---

## 📡 Modulation and Demodulation

Here’s a key challenge:

* Computers communicate using **binary signals (0 and 1)** → square waves
* Transmission systems (like antennas) use **analog signals** → sine waves

👉 Solution: signal conversion

* **Modulation** → digital → analog
* **Demodulation** → analog → digital

📌 The term **modem** comes from:

* **MO** (Modulation)
* **DEM** (Demodulation)

---

## 🌍 How Do We Access Servers?

When you access a website (like Instagram), you're actually connecting to a server.

Servers are identified by numerical addresses called:

👉 **IP Address (Internet Protocol)**

Example:

* Server → `3.244.112.47`
* Your device → `172.23.41.49`

---

## 🔎 Domain Names and DNS

Remembering IP addresses would be very difficult.

👉 That’s why we use domain names like:

* `instagram.com`

This is handled by the DNS.

### How it works:

1. You type `instagram.com`
2. Your device sends a request to a DNS server
3. DNS translates the domain into an IP address
4. You are connected to the correct server

📌 Analogy:
DNS works like a **phone contact list**:

* Name → “Mom”
* Number → actual phone number

---

## 🧭 Routes on the Internet

The Internet does not work in a straight line.

👉 Data travels through **routes (paths)** across the network.

* Packets can take different paths
* The fastest route may change dynamically

📌 Analogy:
Like Waze:

* It recalculates routes based on traffic
* The goal is always the fastest delivery

---

## 📦 Data Packets

When you access content:

* Data is broken into **packets**
* Each packet can travel through different routes
* At the destination, they are reassembled

---

## 🧠 Final Summary

Computers represent data using binary (0 and 1), organized into bytes.
To connect to the internet, devices rely on ISPs and signal conversion (modulation/demodulation).
Websites are accessed using domain names, which are translated into IP addresses via DNS.
Finally, data travels across the internet in packets, following dynamic routes until reaching its destination.

