# 🕵️ Bug Bounty Hunting Companion

This repository contains my personal **Bug Bounty Hunting Companion and Methodology**.

The goal of this project is to create a structured workflow for **reconnaissance, vulnerability discovery, and reporting** during web application security testing.

Instead of randomly testing targets, this Companion helps maintain a **systematic and repeatable approach**.

---

# 🎯 Purpose of This Repository

This repository was created to:

* Maintain a structured **bug bounty methodology**
* Keep track of **testing checklists**
* Document **common vulnerabilities and attack surfaces**
* Improve my **recon workflow**
* Build a personal **bug bounty playbook**

---

# 🔎 Bug Hunting Methodology

## 1️⃣ Target Reconnaissance

* Subdomain enumeration
* Asset discovery
* Technology fingerprinting
* API endpoint discovery
* Directory enumeration

Tools commonly used:

* subfinder
* amass
* assetfinder
* httpx
* ffuf
* dirsearch
* curl

---

## 2️⃣ Attack Surface Mapping

During this phase I try to identify:

* Hidden endpoints
* API routes
* Authentication mechanisms
* File upload functionality
* Admin panels
* Debug endpoints

---

## 3️⃣ Vulnerability Testing Companion

### Authentication & Authorization

* Broken authentication
* IDOR / BOLA
* Privilege escalation
* Session misconfigurations

### Input Validation

* SQL Injection
* XSS
* SSTI
* Command Injection

### Access Control

* Horizontal privilege escalation
* Vertical privilege escalation

### API Testing

* Mass assignment
* Rate limiting issues
* JWT attacks
* GraphQL vulnerabilities

### Server Misconfiguration

* Directory listing
* Default credentials
* Debug endpoints
* Exposed config files

---

# 📂 Repository Structure

```
Companion_bug_hunting
│
├── recon-checklist.md
├── web-vulnerabilities.md
├── api-testing-checklist.md
├── tools-and-commands.md
└── methodology.md
```

---

# 🛠 Tools Used in Bug Hunting

Some tools frequently used during testing:

* Burp Suite
* OWASP ZAP
* ffuf
* sqlmap
* nuclei
* dirsearch
* amass
* curl
* sublist3r

---

# ⚠ Disclaimer

All content in this repository is provided **for educational purposes only**.

Testing should only be performed on systems where **you have explicit permission**.

Unauthorized testing is illegal.

---

# ⭐ Support

If you find this repository useful:

* Star the repo ⭐
* Share with the security community
* Use it as a learning resource

---

## 🤝 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Let's%20connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dheerajkumarjayaswal)

*Open to consulting, collaboration, and security discussions.*

</div>

---

<div align="center">

*Security is not a product. It is a mindset built one vulnerability at a time.*

**#AppSec · #PenTest · #WebSecurity · #APISecuity · #OffensiveSecurity**

</div>
