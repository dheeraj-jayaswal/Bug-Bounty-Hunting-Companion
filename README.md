<div align="center">

# 🕵️ Bug Bounty Hunting Companion

**A curated library of real, publicly-disclosed bug bounty reports — turned into
reproducible checklists.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dheeraj%20Kumar%20Jayaswal-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dheerajkumarjayaswal)
[![GitHub](https://img.shields.io/badge/GitHub-dheeraj--jayaswal-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dheeraj-jayaswal)

</div>

---

## 📌 What This Repository Actually Is

This isn't a generic vulnerability-explainer repo — that's what
[From-Dev-To-Attacker](https://github.com/dheeraj-jayaswal/From-Dev-To-Attacker)
and [AppSec-From-The-Trenches](https://github.com/dheeraj-jayaswal/AppSec-From-The-Trenches)
are for. This repo is a **companion for active bug hunting**: a curated set of
**real, publicly-disclosed HackerOne reports**, broken down into the pattern
that made them work, with an interactive checklist to test for the same
pattern on your own target.

The flagship file is **[`Bounty-Reports.html`](Bounty-Reports.html)** — 30 real
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

## 🧭 How This Differs From My Other Repos

| Repo | What it's for |
|---|---|
| **Bug-Bounty-Hunting-Companion** *(this repo)* | Real disclosed reports → reproducible checklists. Use this when you're actively hunting and want to test a known pattern fast. |
| [From-Dev-To-Attacker](https://github.com/dheeraj-jayaswal/From-Dev-To-Attacker) | Original long-form write-ups on *why* vulnerabilities exist, from a developer's lens, with enterprise domain impact framing. Use this to understand a vulnerability class deeply. |
| [AppSec-From-The-Trenches](https://github.com/dheeraj-jayaswal/AppSec-From-The-Trenches) | Broader enterprise AppSec knowledge base and methodology reference. |

## 📖 How to Use This

1. Pick a phase relevant to what you're testing (auth, injection, SSRF, etc.)
2. Open the report card, read the real scenario
3. Work through the checklist against your target
4. If it hits, use the chain formula as a guide for how far the impact can go
5. Read the pro-tip — that's the reusable lesson, not just the one-off bug

## 👤 About Me

- **Name** — Dheeraj Kumar Jayaswal
- **Role** — Technology Lead – Offensive Security, Infosys Limited
- **Experience** — 15+ years in IT · 5+ years in Offensive Security
- **Domains** — Income Tax · Banking · Retail · E-commerce · Freight Logistics · Education

## ⚠️ Disclaimer

All content here references publicly disclosed reports and is provided for
educational purposes. Test only on systems you own or have explicit permission
to test. Unauthorized testing is illegal.

## 🤝 Connect

[LinkedIn](https://linkedin.com/in/dheerajkumarjayaswal) — open to consulting,
collaboration, and security discussions.

---

<div align="center">

*Real bugs. Real reports. Real checklists.*

**#BugBounty · #AppSec · #PenTest · #WebSecurity · #OffensiveSecurity**

</div>
