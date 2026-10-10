<div align="center">

# 👋 Kunal Richards

### Senior QA Engineer · AI-Powered Test Tooling · Nexsure Platform

![Dyad Inc](https://img.shields.io/badge/Dyad%20Inc-Senior%20QA%20Engineer-1a1a2e?style=for-the-badge)
![Nexsure](https://img.shields.io/badge/Platform-Nexsure-00c853?style=for-the-badge)
![Claude AI](https://img.shields.io/badge/Powered%20by-Claude%20AI-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-Zephyr%20Scale-0052cc?style=for-the-badge&logo=jira&logoColor=white)

</div>

---

## 🧑‍💼 About Me

I'm **Kunal Richards**, a **Senior QA Engineer** at **Dyad Inc**, working on **Nexsure**, an enterprise insurance management platform.

Besides testing the product, I build the tools our QA team uses — most of all **Dyad TestPro**, which writes Zephyr Scale test cases from Jira tickets and has been in regular use by the Nexsure QA team since May 2026.

- 🔬 Functional, regression and integration testing on a large enterprise platform
- 🤖 AI-assisted test design with Claude, grounded in Nexsure domain knowledge
- 🛠️ Full-stack tool building — Node.js, Express, React, TypeScript, SQLite
- 🔐 Security-minded — changes in Jira and Zephyr are made under each engineer's own account
- ✅ Checked releases — unit tests and an endpoint sweep run before changes go live

---

## 🚀 What I Built — Dyad TestPro

> Give it a Jira ticket; it writes the Zephyr Scale test cases and files them in the right sprint folder.
> Designed and built by me, with Claude Code as my AI pair programmer.

<div align="center">

| 📋 Test cases generated | 🎫 Jira tickets covered | 👥 QA engineers using it | ⏱️ Average generation time |
|:---:|:---:|:---:|:---:|
| **5,700+** | **320+** | **9** | **~100 s** |

<sub>From the tool's usage log, 14 April – 7 October 2026.</sub>

</div>

| Feature | What it does |
|---|---|
| 🧠 **AI test generation** | Claude reads the ticket (description, acceptance criteria, comments, linked issues) and writes the cases in up to three passes — baseline → gap fill → review — stopping once coverage is complete. It can also work from an uploaded PDF or Word requirement |
| 📡 **Live streaming** | Test cases appear as they are written |
| 🎯 **Zephyr Scale import** | One click into the right sprint folder and test cycle, linked back to the Jira ticket |
| 📸 **Test Evidence** | Builds a Word evidence document from the ticket's Zephyr test cases, with screenshots placed against each step and a verdict per case — no AI needed |
| 📈 **Insights** (lead view) | Zephyr test-run status, root-cause analysis, escaped defects and QA hygiene |
| 🔌 **MCP server** | The same tools inside Claude Code: get a ticket, generate test cases, import to Zephyr |
| 🔐 **Sign-in and roles** | JWT sign-in, role-based access, bcrypt passwords; changes in Jira and Zephyr are made under each engineer's own account |

**Engineering:** 220+ commits · v2.8.0 · 150+ automated checks plus a read-only sweep of the main API endpoints (as owner, admin and user), run before releases.

---

## 🧰 Tech Stack

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)

</div>

---

## 📌 Projects

### 🧪 Dyad TestPro &nbsp;<sub>(private · internal Dyad tool)</sub>
> AI test case generator and QA workspace for the Nexsure platform: Jira → Claude → Zephyr Scale, Test Evidence documents, QA insights and an MCP server.
>
> **Stack:** Node.js · Express · React/TypeScript · Claude API · Jira REST v3 · Zephyr Scale v2 · SQLite · JWT

### 🧰 Other QA tools I've built
- **Selenium automation framework** — Java, Selenium 4, TestNG and Maven, with JSON-driven tests, a REST Assured API smoke suite and Allure reports
- **AI Jira QA reporter** — turns a Jira ticket into a structured QA report: reproduction steps, root-cause analysis and test scenarios (Node.js + React + Claude)
- **Test coverage analyser** — maps Zephyr test cases to Nexsure modules and compares them with recent GitHub changes to show coverage gaps

---

## 📊 How I Work

```
✅  Test what the ticket actually changed, in the environment it was fixed in.
✅  If the team repeats a task every day, build a tool for it.
✅  Changes in Jira and Zephyr are made under the engineer's own account, so the history shows who did what.
✅  Track usage, cost and coverage, and say which numbers are estimates.
✅  Run the checks before saying "fixed".
```

---

## 🏅 Highlights

- Designed and built **Dyad TestPro** in early 2026; in regular use by the Nexsure QA team since May 2026
- About **100 seconds** to generate a full set of test cases for a ticket (about 12 cases on average), filed straight into the right Zephyr sprint folder
- **5,700+ test cases generated** across **320+ Jira tickets**, **3,600+ of them imported into Zephyr Scale**
- Ran the tool's security reviews and dependency audits (April and October 2026), the latest ahead of its move to AWS
- Joined **Claude AI, Jira and Zephyr Scale** into one workflow, from ticket to test cases to evidence

---

## 🌐 Areas of Expertise

<div align="center">

| Domain | Tools & Skills |
|---|---|
| **Test Management** | Jira, Zephyr Scale, test cycles, sprint folders, coverage links |
| **AI Integration** | Claude API, Claude Code, prompt design, multi-pass generation, MCP |
| **Automation** | Selenium, Java, TestNG, REST Assured, Allure |
| **Backend** | Node.js, Express, REST APIs, SQLite, JWT |
| **Frontend** | React, TypeScript, Vite, Server-Sent Events |
| **Security** | JWT auth, bcrypt, Helmet, per-user credentials, dependency audits |
| **Delivery** | Git, GitHub, automated release checks, Windows and Linux |

</div>

---

<div align="center">

**Dyad Inc · Nexsure Platform · Senior QA Engineering**

</div>
