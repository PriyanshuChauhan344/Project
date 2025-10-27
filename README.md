# Project
# 🔒 Web Application Vulnerability Scanner

A simple *Python + Flask* project that scans websites for common vulnerabilities like *SQL Injection (SQLi)* and *Cross-Site Scripting (XSS)* based on the OWASP Top 10 standards.

---

## 🚀 Features

- 🕸 Crawls all internal pages and forms of a target website  
- 💣 Tests for:
  - SQL Injection (SQLi)
  - Cross-Site Scripting (XSS)
- 📊 Displays scan results on a web dashboard (Flask UI)
- ⚙ Built using Python, Flask, Requests, and BeautifulSoup4
- 🧾 Simple and easy to extend for other vulnerabilities

---

## 🧠 How It Works

1. You enter a website URL in the web interface.  
2. The scanner *crawls* the site and collects all links and input fields.  
3. It sends test payloads to detect common vulnerabilities (SQLi, XSS).  
4. The results are displayed in a simple Flask dashboard showing URLs, payloads, and evidence.

---

## 🧰 Tech Stack

| Component | Technology Used |
|------------|-----------------|
| *Language* | Python |
| *Framework* | Flask |
| *Libraries* | Requests, BeautifulSoup4 |
| *Frontend* | HTML, CSS (basic Flask templates) |
