<!--
  À REMPLACER AVANT DE PUBLIER :
    YOUR-USERNAME  -> ton pseudo GitHub
    YOUR-LINKEDIN  -> ton slug LinkedIn
    ton.email@example.com
    ton-portfolio.com
-->

<div align="center">

# Doua Gannouni

### Computer Engineer · Full-Stack · QA Automation · AI Workflows

**Building reliable software through clean development, structured testing, and intelligent automation.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-LINKEDIN)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ton.email@example.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-6366F1?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://ton-portfolio.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR-USERNAME)

![Tunisia](https://img.shields.io/badge/Tunisia-1E1B4B?style=flat-square)
![Open to Relocation](https://img.shields.io/badge/Open_to_Relocation_&_Remote-4C1D95?style=flat-square)
![Languages](https://img.shields.io/badge/French_·_English_·_Arabic-5B21B6?style=flat-square)
![Available](https://img.shields.io/badge/Open_to_opportunities-059669?style=flat-square)

</div>

---

## About Me

I am **Doua Gannouni**, a **Computer Engineer** specializing in Software Engineering, Full-Stack Web Development, and QA Automation.

Most engineers **build**. Most testers **verify**. I do both — and I automate the bridge between them with AI-driven pipelines.

- **Full-Stack Development** — MERN stack with a focus on robust, maintainable architecture
- **QA & Software Testing** — end-to-end automation, BDD/Gherkin frameworks, Page Object Model suites
- **AI & Automation** — AI-assisted QA workflows, CI pipelines, and n8n orchestration
- **Dual Perspective** — bridging software creation and quality validation for zero-defect releases

---

## Core Focus Areas

| Development | Quality Assurance | Automation & AI |
| :--- | :--- | :--- |
| Responsive Interfaces | Functional & E2E Testing | n8n Workflow Orchestration |
| RESTful API Architecture | BDD / Gherkin Scenarios | LLM / ReAct QA Agents |
| Authentication & Security | Page Object Model Suites | CI Pipelines & Docker |
| Database Modeling | Regression Strategy | Ephemeral Preview Environments |
| Clean Maintainable Code | Allure Evidence Reporting | Jira-Driven Automation |

---

## Featured Project — Intelligent QA Automation Ecosystem

> **Final-Year Engineering Project** · *Webify Technology*
>
> A self-driving QA pipeline: a Jira ticket changes status, an AI agent reasons, executes real browser and mobile tests, then writes its verdict back to Jira — with no human in the loop.

```mermaid
flowchart LR
    A["Jira Ticket"] --> B["n8n Orchestrator"]
    B --> C["AI QA Agent"]
    C --> D{"Platform"}
    D -->|Web| E["Playwright + TS"]
    D -->|Mobile| F["Appium"]
    E --> G["BDD / POM Execution"]
    F --> G
    G --> H{"Verdict"}
    H -->|PASS| I["Ticket Validated"]
    H -->|FAIL| J["Allure Report"]
    J --> K["Defect Enriched"]
    K --> I

    classDef src  fill:#1E1B4B,color:#fff,stroke:#818CF8,stroke-width:2px;
    classDef proc fill:#0E7490,color:#fff,stroke:#22D3EE,stroke-width:2px;
    classDef dec  fill:#581C87,color:#fff,stroke:#C084FC,stroke-width:2px;
    classDef ok   fill:#065F46,color:#fff,stroke:#34D399,stroke-width:2px;
    classDef ko   fill:#7F1D1D,color:#fff,stroke:#F87171,stroke-width:2px;
    class A src;
    class B,C,E,F,G proc;
    class D,H dec;
    class I ok;
    class J,K ko;
```

<details>
<summary><b>Click to expand — engineering deep dive</b></summary>

**AI Agent**
- ReAct reasoning loop (Perception, Reasoning, Action) on a layered Node.js agent
- Guardrails against CAPTCHA/OTP dead-ends and false-success detection
- Structured verdict payload pushed back to Jira with evidence links

**Test Framework**
- BDD / Gherkin feature files mapped to reusable Page Object Model classes
- Shared step definitions across web and mobile suites
- Allure reports with traces, screenshots, and video on failure

**Infrastructure**
- Three n8n workflows: auto ticket generation, AI agent validation, ephemeral sandbox deployment
- One isolated preview environment per Git branch (Docker + dynamic routing + secure public tunnel)
- GitLab CI triggering the full chain on push
- Documented with UML sequence, activity, and component diagrams (PlantUML)

</details>

---

## Technical Stack

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Databases**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**QA & Testing**

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Appium](https://img.shields.io/badge/Appium-662D91?style=for-the-badge&logo=appium&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)
![Cucumber](https://img.shields.io/badge/Cucumber-23D96C?style=for-the-badge&logo=cucumber&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Allure](https://img.shields.io/badge/Allure-FF6C1F?style=for-the-badge&logo=qameta&logoColor=white)

**DevOps & AI**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![LLM Agents](https://img.shields.io/badge/LLM_Agents-412991?style=for-the-badge&logo=openai&logoColor=white)

---

## Experience

| Year | Role | Company | Impact |
| :---: | :--- | :--- | :--- |
| **2026** | QA Automation & AI Engineer | Webify Technology | Autonomous AI testing agent, n8n orchestration & per-branch preview environments |
| **2024** | Full-Stack MERN Intern | BeeCoders | E-learning platform modules with AI-powered features |
| **2023** | Full-Stack Developer | Capstone Project | Business information system & executive dashboards |
| **2022** | Laravel Developer Intern | Real Estate Platform | Dynamic modules & relational database schemas |
| **2021** | Front-End Developer Intern | Maritime Services | Responsive UI design & performance optimization |

---

## How I Work

<div align="center">

**UNDERSTAND** → **DESIGN** → **BUILD** → **TEST** → **IMPROVE**

*business need → architecture first → clean & modular → automated proof → measure & iterate*

</div>

---

## GitHub Stats

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=YOUR-USERNAME&show_icons=true&hide_border=true&title_color=8B5CF6&icon_color=22D3EE&include_all_commits=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR-USERNAME&layout=compact&hide_border=true&title_color=8B5CF6&langs_count=8)

</div>

---

<div align="center">

## Let's Connect

Open to **Software Engineer**, **QA Automation Engineer**, and **Full-Stack** roles — including relocation and visa sponsorship.

[![Connect on LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-LINKEDIN)
[![Send an Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ton.email@example.com)

**BUILD THOUGHTFULLY · TEST CAREFULLY · IMPROVE CONTINUOUSLY**

© 2026 Doua Gannouni · Computer Engineer

</div>
