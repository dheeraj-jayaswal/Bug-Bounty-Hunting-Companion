<div align="center">

# 🕵️ Bug Bounty Hunting Companion

**A curated library of real, publicly-disclosed bug bounty reports — turned into
reproducible checklists.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dheeraj%20Kumar%20Jayaswal-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dheerajkumarjayaswal)
[![GitHub](https://img.shields.io/badge/GitHub-dheeraj--jayaswal-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dheeraj-jayaswal)
[![Live Site](https://img.shields.io/badge/🌐%20Live%20Interactive%20Site-View%20Now-2ECC71?style=for-the-badge)](https://dheeraj-jayaswal.github.io/Bug-Bounty-Hunting-Companion/)

</div>

---

> ⚠️ **Note:** The checklists in this repo are interactive HTML pages. GitHub's
> normal file viewer shows raw source code, not the working page. **Always
> open files via the live site** →
> **https://dheeraj-jayaswal.github.io/Bug-Bounty-Hunting-Companion/**

---

## 📌 What This Repository Actually Is

This isn't a generic vulnerability-explainer repo — that's what
[From-Dev-To-Attacker](https://github.com/dheeraj-jayaswal/From-Dev-To-Attacker)
and [AppSec-From-The-Trenches](https://github.com/dheeraj-jayaswal/AppSec-From-The-Trenches)
are for. This repo is a **companion for active bug hunting**: a curated set of
**real, publicly-disclosed HackerOne reports**, broken down into the pattern
that made them work, with an interactive checklist to test for the same
pattern on your own target.

The flagship file is **[`Bounty-Reports.html`](https://dheeraj-jayaswal.github.io/Bug-Bounty-Hunting-Companion/Bounty-Reports.html)** — 30 real
disclosed reports, organized into 6 phases:

1. IDOR & Business Logic Flaws
2. Browser & Client-Side Bugs
3. Authentication & Session Bugs
4. Injection & XSS Attacks
5. Privacy, Info Disclosure & Cloud Bugs
6. Race Conditions, SSRF & Privilege Escalation

Each report card includes:

| Element | What it gives you |
|---|---|
| 🔗 **Link to the real report** | The original public disclosure, so you can read the full story |
| 📋 **Scenario summary** | The bug explained in plain language |
| ✅ **Execution checklist** | Interactive, tickable steps to test the same pattern yourself |
| ⛓️ **Chain formula** | How the bug escalated from initial finding to full impact |
| 💡 **Pro tip / veteran mindset note** | The generalizable lesson behind the specific bug |

---


## 🧭 How This Fits With My Other Repos

| Repository | What's in it |
|---|---|
| **[Bug-Bounty-Hunting-Companion](https://github.com/dheeraj-jayaswal/Bug-Bounty-Hunting-Companion)** *(this repo)* | Real, publicly-disclosed bug bounty reports broken into reproducible checklists |
| [From-Dev-To-Attacker](https://github.com/dheeraj-jayaswal/From-Dev-To-Attacker) | My flagship field journal — 67 original write-ups on vulnerability patterns, written from a developer's lens, with enterprise domain-impact framing across Income Tax, Banking, Retail, E-commerce, Freight Logistics, and Education |
| [CICD-Goat-Vapt-Writeup](https://github.com/dheeraj-jayaswal/CICD-Goat-Vapt-Writeup) | Full VAPT writeup against OWASP CICD-Goat — 16 findings including CVE-2024-23897, mapped to the OWASP Top 10 CI/CD Security Risks, with PoCs and interview-ready summaries |
| [From-Pentester-To-Red-Teamer](https://github.com/dheeraj-jayaswal/From-Pentester-To-Red-Teamer) | My structured 24-month roadmap for transitioning from Web/API pentesting into Red Teaming — phases, labs, certifications, and progress tracked openly as I work through it |
| [AppSec-From-The-Trenches](https://github.com/dheeraj-jayaswal/AppSec-From-The-Trenches) | Pentest tools & methodology reference — how I actually use Burp Suite, Nmap, Metasploit, Hydra, Hashcat, and more, plus my WAPT methodology |
| [API-From-The-Trenches](https://github.com/dheeraj-jayaswal/API-From-The-Trenches) | Deep-dive API security series — OWASP API Top 10 coverage, BOLA, JWT attacks, GraphQL testing, full methodology |
| [DarkWeb-From-The-Trenches](https://github.com/dheeraj-jayaswal/DarkWeb-From-The-Trenches) | Threat intelligence & dark web OSINT methodology — credential leak monitoring, ransomware tracking, pre-engagement TI |
| [.pcap-Arsenal](https://github.com/dheeraj-jayaswal/.pcap-Arsenal) | Packet captures organized by protocol, for Web/API/Network-layer analysis and learning |

---


## 🧭 How This Differs From My Other Repos

| Repo | What it's for |
|---|---|
| **Bug-Bounty-Hunting-Companion** *(this repo)* | Real disclosed reports → reproducible checklists. Use this when you're actively hunting and want to test a known pattern fast. |
| [From-Dev-To-Attacker](https://github.com/dheeraj-jayaswal/From-Dev-To-Attacker) | Original long-form write-ups on *why* vulnerabilities exist, from a developer's lens, with enterprise domain impact framing. Use this to understand a vulnerability class deeply. |
| [AppSec-From-The-Trenches](https://github.com/dheeraj-jayaswal/AppSec-From-The-Trenches) | Broader enterprise AppSec knowledge base and methodology reference. |

## 📖 How to Use This

1. Go to the **[live site](https://dheeraj-jayaswal.github.io/Bug-Bounty-Hunting-Companion/)** — don't browse the raw `.html` files directly on github.com, they won't render
2. Pick a phase relevant to what you're testing (auth, injection, SSRF, etc.)
3. Open the report card, read the real scenario
4. Work through the checklist against your target
5. If it hits, use the chain formula as a guide for how far the impact can go
6. Read the pro-tip — that's the reusable lesson, not just the one-off bug

---


## 🧠 Testing Philosophy

> *"The best penetration testers think like developers first and attackers second. If you understand why code was written a certain way, you'll always find more than a scanner ever will."*

I approach every engagement in three phases:

**1. Understand before you attack** — Read the application. Use it as a real user. Understand the business logic before touching a single tool.

**2. Manual first, tools second** — Automated scanners find what they're configured to find. The interesting bugs are always found by thinking, not scanning.

**3. Report like a developer** — A finding that developers can't understand or reproduce is a finding that doesn't get fixed.

---


## 👤 About Me

- **Name** — Dheeraj Kumar Jayaswal
- **Role** — Technology Lead – Offensive Security, Infosys Limited
- **Focus** — Web Application & API Penetration Testing
- **Experience** — 15+ years in IT · 6+ years in Offensive Security
- **Edge** — Former full-stack developer (ASP.NET / SQL Server) — I think like a developer, attack like a hacker
- **Domains** — Income Tax · Banking · Retail · E-commerce · Freight Logistics · Education

---


## 🏅 Certifications

| Certification | Issuer | Status |
|---|---|---|
| Certified Ethical Hacker (CEH) | EC-Council | ✅ 2021 |
| AWS Certified Solutions Architect – Associate | Amazon Web Services | ✅ 2022 |
| AWS Certified Cloud Practitioner | Amazon Web Services | ✅ 2022 |
| Executive Certificate in Cyber Security | IIT Kanpur | ✅ 2026 |
| OSWE — OffSec Web Expert (OSCE3 track) | OffSec | 🔄 In Progress |

**Future direction — Red Teaming:** OSCP → CRTO → OSEP, CRTP, CRTL, CRTE

---


## ⚠️ Disclaimer

All content here references publicly disclosed reports and is provided for
educational purposes. Test only on systems you own or have explicit permission
to test. Unauthorized testing is illegal.

## 📄 License

[![License](https://img.shields.io/badge/license-CC%20BY%204.0-blue)](LICENSE.md)
[![Last Commit](https://img.shields.io/github/last-commit/dheeraj-jayaswal/Bug-Bounty-Hunting-Companion)](https://github.com/dheeraj-jayaswal/Bug-Bounty-Hunting-Companion/commits/main)

⭐ If this helped you, consider starring the repo — it helps others find it too.

## 🤝 Connect

[LinkedIn](https://linkedin.com/in/dheerajkumarjayaswal) — open to consulting,
collaboration, and security discussions.

---

<div align="center">

*Real bugs. Real reports. Real checklists.*

**#BugBounty · #AppSec · #PenTest · #WebSecurity · #OffensiveSecurity**

</div>
