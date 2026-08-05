<!--
GitHub Profile README — Doua Gannouni
Professional, self-contained, and recruiter-focused.
No external images, GIFs, badges, or imported assets.
-->

<div align="center">

👩‍💻 Doua Gannouni

Computer Engineer · Full-Stack Development · QA Automation

Building reliable web solutions through development, systematic testing, and intelligent automation.

<br/>

<kbd>BUILD</kbd> → <kbd>TEST</kbd> → <kbd>AUTOMATE</kbd> → <kbd>IMPROVE</kbd>

<br/><br/>

Portfolio • LinkedIn • Email

</div>

👋 About Me

I am Doua Gannouni, a Computer Engineer specialized in Software Engineering.

My background includes full-stack web development, software testing, and QA automation, with practical experience gained through internships and academic projects. I mainly work with the MERN stack and modern testing tools, while exploring AI-assisted QA, workflow automation, and Big Data.

I approach software from two complementary perspectives: development and quality.

🎯 Core Expertise

💻 Full-Stack Development

🧪 Quality Engineering

⚙️ Intelligent Automation

Responsive web interfaces

Functional and regression testing

Automated test workflows

REST APIs and authentication

End-to-end validation

BDD and Page Object Model

Database-driven applications

Defect tracking and reporting

CI/CD and orchestration

Maintainable architectures

Evidence-based quality

AI-assisted validation

🚀 Featured Engineering Project

Intelligent QA Automation Ecosystem

For my final-year engineering project at Webify Technology, I designed a reusable QA automation ecosystem connecting issue tracking, intelligent orchestration, automated test execution, and reporting.

Objective: reduce repetitive QA work, improve traceability, and accelerate ticket validation through automation and AI-assisted analysis.

flowchart TB

    Jira["🎫 Jira Ticket<br/>Bug or validation request"]
    N8N["⚙️ n8n Workflow<br/>Process orchestration"]
    Agent["🤖 AI QA Agent<br/>Ticket analysis and test planning"]

    Jira --> N8N
    N8N --> Agent

    Agent --> Decision{"Select test path"}

    subgraph Execution["AUTOMATED TEST EXECUTION"]
        direction LR

        Web["🌐 Web Testing<br/>Playwright + TypeScript"]
        Mobile["📱 Application Testing<br/>Appium"]
        Framework["🧩 Test Architecture<br/>BDD · Gherkin · POM"]

        Web --> Framework
        Mobile --> Framework
    end

    Decision -->|Web| Web
    Decision -->|Application| Mobile

    Framework --> Verdict{"Test verdict"}

    Verdict -->|Passed| Success["✅ Validation Result"]
    Verdict -->|Failed| Evidence["📊 Allure Evidence<br/>Logs · Screenshots · Results"]

    Evidence --> Defect["🐞 Jira Defect Update"]
    Success --> Feedback["🔄 Automated Jira Feedback"]
    Defect --> Feedback

    Feedback --> CICD["🐳 Docker · GitLab CI/CD"]

    classDef entry fill:#312e81,color:#ffffff,stroke:#a5b4fc,stroke-width:2px;
    classDef automation fill:#172554,color:#ffffff,stroke:#38bdf8,stroke-width:2px;
    classDef ai fill:#4c1d95,color:#ffffff,stroke:#c084fc,stroke-width:2px;
    classDef decision fill:#713f12,color:#ffffff,stroke:#fbbf24,stroke-width:2px;
    classDef test fill:#164e63,color:#ffffff,stroke:#22d3ee,stroke-width:2px;
    classDef success fill:#064e3b,color:#ffffff,stroke:#34d399,stroke-width:2px;
    classDef failure fill:#7f1d1d,color:#ffffff,stroke:#f87171,stroke-width:2px;
    classDef devops fill:#1e293b,color:#ffffff,stroke:#94a3b8,stroke-width:2px;

    class Jira entry;
    class N8N automation;
    class Agent ai;
    class Decision,Verdict decision;
    class Web,Mobile,Framework test;
    class Success,Feedback success;
    class Evidence,Defect failure;
    class CICD devops;

<details>
<summary><strong>🔍 Explore the Technical Implementation</strong></summary>

<br/>

Layer

Technologies

Responsibility

Issue Management

Jira

Ticket tracking, comments, transitions, and defect updates

Orchestration

n8n

Workflow coordination and communication between services

AI Analysis

OpenAI-powered QA agent

Ticket interpretation, test planning, and automated validation

Web Automation

Playwright, TypeScript

Functional, regression, and end-to-end web testing

Application Automation

Appium

Automated application test execution

Test Architecture

BDD, Gherkin, POM

Reusable scenarios, steps, pages, and test flows

Reporting

Allure Report

Results, logs, screenshots, and execution evidence

Infrastructure

Docker, GitLab CI/CD

Reproducible environments and automated execution

</details>

Main Contributions

Designed a reusable BDD and Page Object Model architecture

Automated web scenarios using Playwright and TypeScript

Implemented automated application testing with Appium

Connected test execution with Jira and Allure

Orchestrated QA workflows through n8n

Integrated an AI-assisted QA agent for ticket analysis

Containerized the solution with Docker

Integrated automated execution into GitLab CI/CD

<div align="center">

Explore the Complete Project on My Portfolio →

</div>

🧰 Technical Toolbox

<details open>
<summary><strong>💻 Full-Stack Development</strong></summary>

<br/>

React.js · JavaScript · TypeScript · Node.js · Express.jsMongoDB · MySQL · Laravel · PHP · REST APIsHTML5 · CSS3 · Tailwind CSS · Bootstrap

</details>

<details open>
<summary><strong>🧪 Software Testing & QA Automation</strong></summary>

<br/>

Playwright · Selenium · Appium · BDD / GherkinPage Object Model · Functional Testing · Regression TestingEnd-to-End Testing · Allure Report · Jira

</details>

<details>
<summary><strong>⚙️ DevOps, Automation & AI</strong></summary>

<br/>

Git · GitHub · GitLab CI/CD · Docker · Postmann8n · OpenAI API · Gemini API · Python

</details>

💼 Experience

Period

Role

Main Contribution

2026

QA Automation & AI Engineering Intern · Webify Technology

Intelligent testing ecosystem using Playwright, Appium, Jira, Allure, n8n, Docker, and AI

2024

Full-Stack MERN Developer Intern · BeeCoders

E-learning platform with REST APIs, authentication, notifications, and AI-powered features

2023

Full-Stack MERN Developer · Final-Year Project

Business information system for clients, projects, employees, invoices, documents, and dashboards

2022

Laravel Web Developer Intern

Development and testing of modules for a real-estate platform

2021

Front-End Developer Intern

Responsive website presenting maritime services

🧭 Engineering Approach

<div align="center">

<kbd>UNDERSTAND</kbd> → <kbd>DESIGN</kbd> → <kbd>BUILD</kbd> → <kbd>TEST</kbd> → <kbd>AUTOMATE</kbd> → <kbd>IMPROVE</kbd>

</div>

<br/>

Principle

What It Means

Clarity

Understand the real need before selecting a technical solution

Reliability

Validate expected behavior with traceable evidence

Maintainability

Build reusable structures that are easier to evolve

Automation

Reduce repetitive work while preserving control and visibility

Learning

Improve continuously through feedback and experimentation

🌍 Professional Direction

I am open to junior and graduate opportunities worldwide involving:

Full-Stack Web Development

Software Testing

QA Automation

Intelligent workflow automation

AI-assisted software solutions

I value clear communication, continuous learning, maintainable code, and evidence-based quality.

<div align="center">

🤝 Let’s Build Reliable Software Together

Open to junior and graduate opportunities worldwide inFull-Stack Development, Software Testing, and QA Automation.

<br/>

Explore My Portfolio • Connect on LinkedIn • Contact Me

<br/><br/>

<sub>
<strong>BUILD THOUGHTFULLY · TEST CAREFULLY · IMPROVE CONTINUOUSLY</strong>
</sub>

<br/><br/>

<sub>© 2026 Doua Gannouni · Computer Engineer</sub>

</div>
