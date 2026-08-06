<!--
  ═══════════════════════════════════════════════════════════════
  DOUA GANNOUNI · GitHub Profile README
  À FAIRE AVANT DE PUBLIER :
   1) Uploade  header.svg  dans le repo (à la racine, à côté du README)
   2) Remplace (rechercher/remplacer) :
        YOUR-USERNAME  ->  ton pseudo GitHub
        YOUR-LINKEDIN  ->  ton slug LinkedIn
        ton.email@example.com
        ton-portfolio.com
  ═══════════════════════════════════════════════════════════════
-->

<!-- HEADER SUR MESURE (pipeline animé) -->
<p align="center">
  <img src="./header.svg" width="100%" alt="Doua Gannouni — Autonomous QA pipeline"/>
</p>

<p align="center">
  <a href="https://linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:ton.email@example.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://ton-portfolio.com"><img src="https://img.shields.io/badge/Portfolio-6366F1?style=for-the-badge&logo=firefoxbrowser&logoColor=white"/></a>
  &nbsp;·&nbsp;
  <img src="https://img.shields.io/badge/🌍_Open_worldwide_·_visa_sponsorship-14102B?style=for-the-badge"/>
</p>

---

## `whoami`

```ts
const doua = {
  title:    "Computer Engineer",
  edge:     "I build the product AND the system that proves it works",
  builds:   ["MERN apps", "REST APIs", "clean architecture"],
  breaks:   ["E2E suites", "BDD/POM frameworks", "regression traps"],
  automates:["n8n workflows", "AI QA agents", "CI pipelines"],
  speaks:   ["French", "English", "Arabic"],
  status:   "open to opportunities — relocation welcome",
};
```

Most engineers **build**. Most testers **verify**.
I sit where the two meet — and I let **AI agents run the tests for me.**

---

## The thing I'm proud of

An **autonomous QA pipeline** where software tests itself.
A Jira ticket changes status → an AI agent *reasons* about what to check → it drives real browser and mobile tests → then writes its own verdict back to Jira. No human clicks anything.

```mermaid
flowchart LR
    A["Jira Ticket"]:::src --> B["n8n Orchestrator"]:::proc
    B --> C["AI QA Agent<br/><i>reason → act</i>"]:::proc
    C --> D{"Web or Mobile?"}:::dec
    D -->|Web| E["Playwright + TS"]:::proc
    D -->|Mobile| F["Appium"]:::proc
    E --> G["BDD · POM"]:::proc
    F --> G
    G --> H{"Verdict"}:::dec
    H -->|PASS| I["Ticket Validated"]:::ok
    H -->|FAIL| J["Allure evidence<br/>→ defect reopened"]:::ko
    J --> A

    classDef src  fill:#1E1B4B,color:#fff,stroke:#818CF8,stroke-width:2px;
    classDef proc fill:#0E7490,color:#fff,stroke:#22D3EE,stroke-width:2px;
    classDef dec  fill:#581C87,color:#fff,stroke:#C084FC,stroke-width:2px;
    classDef ok   fill:#065F46,color:#fff,stroke:#34D399,stroke-width:2px;
    classDef ko   fill:#7F1D1D,color:#fff,stroke:#F87171,stroke-width:2px;
```

<details>
<summary><b>What's actually hard about it →</b></summary>

- The agent runs a **ReAct loop** (reason, then act) — not a fixed script — so it adapts to what the app does.
- **Guardrails** stop it from faking success on a CAPTCHA/OTP wall or reporting a false pass.
- Every Git branch spins up its **own isolated preview environment** (Docker + dynamic routing + secure public tunnel), tested, then torn down.
- Three cooperating n8n workflows: ticket generation, agent validation, sandbox deployment.

</details>

---

## What I reach for

<table>
<tr>
<td><b>Build</b></td>
<td>

`React` `TypeScript` `Node.js` `Express` `Laravel` `MongoDB` `MySQL` `Tailwind`

</td>
</tr>
<tr>
<td><b>Break</b></td>
<td>

`Playwright` `Appium` `Selenium` `Cucumber` `Postman` `Allure`

</td>
</tr>
<tr>
<td><b>Automate</b></td>
<td>

`n8n` `Docker` `GitLab CI` `Jira` `Python` `LLM agents`

</td>
</tr>
</table>

---

## How I think about a problem

```mermaid
flowchart LR
    U(("understand")):::s --> D(("design")):::s --> B(("build")):::s --> T(("test")):::s --> I(("improve")):::s
    I -.->|loop| U
    classDef s fill:#2A1B5A,color:#E9D5FF,stroke:#A78BFA,stroke-width:2px;
```

> Understand the *why* before the *what* · design before code · prove it with automation · then measure and iterate.

---

<p align="center">
  <b>Let's build software that proves itself.</b><br/><br/>
  <a href="https://linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/Reach_out_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:ton.email@example.com"><img src="https://img.shields.io/badge/Say_hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p align="center"><sub><code>build thoughtfully · test carefully · improve continuously</code></sub></p>
