# 👻 GhostRoot CTF

> A lightweight, interactive, beginner-friendly Cybersecurity CTF (Capture The Flag) platform built for learning web security fundamentals—no login or backend required.

Live Demo: [https://atul-vaibhav.github.io/ghostroot-ctf/](https://atul-vaibhav.github.io/ghostroot-ctf/)

---

## 📌 About The Project

**GhostRoot CTF** is designed specifically for students, absolute beginners, and cybersecurity enthusiasts who want to learn practical web security concepts through hands-on challenges. The platform requires **zero setup**, runs entirely in the browser, and saves your progress locally.

---

## 🔥 Key Features

* **No Sign-In Required:** Start solving challenges immediately upon visiting the page.
* **10 Cybersecurity Topics:** Covers essential topics from basic HTML inspection to advanced web vulnerabilities.
* **30 MCQs & 30 Practical CTF Challenges:** Graded across 3 difficulty levels:
  * 🟢 **Easy** (50 PTS)
  * 🟡 **Moderate** (100 PTS)
  * 🔴 **Hard** (150 PTS)
* **Interactive Sandbox Modules:** Built-in tools for decoding Base64/ROT13/Hex, SQLi query tester, XSS sandbox execution, terminal command simulators, and header manipulation.
* **Progress Tracking:** Score and completed flags are automatically stored in browser `localStorage`.
* **Progressive Hints:** Stuck on a challenge? Reveal hints step-by-step.
* **Dark Cyber-Themed UI:** Clean, responsive design styled with Tailwind CSS and FontAwesome icons.

---

## 📚 Topics Covered

1. **Source Code & DevTools:** Discovering hidden HTML comments, hidden form inputs, and `localStorage` keys.
2. **Encoding & Cryptography:** Decoding Base64 strings, ROT13 ciphers, and Hexadecimal to ASCII.
3. **SQL Injection (SQLi):** Authentication bypass (`' OR 1=1 --`), `UNION SELECT` data extraction, and Boolean Blind SQLi.
4. **Cross-Site Scripting (XSS):** Reflected `<script>` injection, HTML event handlers (`onerror`), and DOM `href` attribute contexts.
5. **Information Leakage & Recon:** Fetching server `/robots.txt`, exposed `.env` configs, and hidden API endpoints.
6. **OS Command Injection:** Semicolon chaining (`;`), output piping (`|`), and space filters (`$IFS`).
7. **Directory Traversal (LFI):** Basic relative paths (`../../`), non-recursive filter bypasses, and URL encoding (`%2e%2e%2f`).
8. **Broken Session & Cookies:** Cookie role tampering, JWT claim manipulation, and sequential session ID prediction.
9. **Insecure Direct Object References (IDOR):** URL parameter tampering, JSON payload modification, and HTTP Parameter Pollution (HPP).
10. **File Upload Vulnerabilities:** Executable uploads (`.php`), double-extension bypasses (`.php.jpg`), and `Content-Type` MIME spoofing.

---

## 🛠️ Tech Stack

* **HTML5** & **Vanilla JavaScript (ES6)**
* **Tailwind CSS** (via CDN)
* **FontAwesome 6** (for icons)
* **GitHub Pages** (for static hosting)

---

## 🚀 Quick Start (Local Setup)

1. Clone or download this repository:
   ```bash
   git clone https://github.com/Atul-vaibhav/ghostroot-ctf.git
   ```
2. Open `index.html` directly in any web browser.

---

## 📄 Short Repository Tagline (For GitHub Header)

> **Short Description:**
> *Lightweight, beginner-friendly Cybersecurity CTF learning platform covering 10 topics with interactive MCQs and practical web challenges.*