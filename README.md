<!-- DOUA GANNOUNI · GitHub Profile README -->

<p align="center">
  <img src="./header.svg" width="100%" alt="Doua Gannouni — Software Engineer" />
</p>

<p align="center">
  <a href="https://portfolio.doua-automation.xyz/"><img src="https://img.shields.io/badge/Portfolio-View_my_work-22D3EE?style=for-the-badge&logo=firefoxbrowser&logoColor=07111F&labelColor=0B172A" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/gannounidoua"><img src="https://img.shields.io/badge/LinkedIn-Connect-38BDF8?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0B172A" alt="LinkedIn" /></a>
  <a href="mailto:gannounidoua09@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-F4C95D?style=for-the-badge&logo=gmail&logoColor=07111F&labelColor=0B172A" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Fresh_graduate-2026-0B172A?style=flat-square&logo=academia&logoColor=F4C95D" alt="Fresh graduate 2026" />
  <img src="https://img.shields.io/badge/Monastir-Tunisia-0B172A?style=flat-square&logo=googlemaps&logoColor=22D3EE" alt="Monastir, Tunisia" />
  <img src="https://img.shields.io/badge/Open_to-relocation_and_international_roles-0B172A?style=flat-square&logo=googleearth&logoColor=22D3EE" alt="Open to relocation and international roles" />
</p>

---

## `01 · About me`

I am a **newly graduated Software Engineer** based in Tunisia. My profile combines **full-stack web development** with **manual and automated software testing**.

Through internships, final-year projects, academic projects, and personal work, I have built web applications, prepared and executed test scenarios, documented defects, and automated web and Android user journeys.

At this stage of my career, my experience is primarily **project- and internship-based**. I am looking for a junior position where I can contribute from the start, learn from an experienced team, and continue growing in software quality and development.

### What I can contribute

- Develop and maintain web features with **React, TypeScript, Node.js, Express, and databases**.
- Translate requirements into **test cases, execution results, and clear defect reports**.
- Automate web and mobile scenarios using **Playwright, Appium, Selenium, BDD, and Page Objects**.
- Produce traceable test evidence with **Allure, Jira, and TestLink**.
- Support automation workflows and delivery environments with **n8n, Docker, Git, and GitLab CI/CD**.

---

## `02 · Featured engineering project`

### Intelligent Web & Mobile Test Automation

**Context:** 2026 engineering final project at **Webify Technology**  
**Target application:** a taxi-booking solution with customer/admin web interfaces and an Android driver application  
**Project status:** engineering project and working proof of concept

The objective was to reduce repetitive manual work by connecting test execution, evidence, reporting, and Jira follow-up in one coherent workflow.

My work included:

- Structuring TypeScript test code with **Gherkin/BDD, Page Object Model, and reusable Flows**.
- Automating web journeys with **Playwright** and Android journeys with **Appium**.
- Generating **Allure reports** with screenshots and execution evidence.
- Connecting **Jira and n8n** to trigger workflows and return test results to tickets.
- Exploring an **AI-assisted QA agent prototype** able to observe a flow and choose controlled test actions.
- Designing isolated test environments with **Docker, GitLab CI/CD, Traefik, and Cloudflare Tunnel**.

```mermaid
flowchart LR
    A["Jira ticket"]:::source --> B["n8n workflow"]:::process
    B --> C{"Test target"}:::decision
    C -->|Web| D["Playwright"]:::process
    C -->|Android| E["Appium"]:::process
    D --> F["Allure evidence<br/>+ Jira result"]:::result
    E --> F
    F -. feedback .-> A

    classDef source fill:#0B172A,color:#F8FAFC,stroke:#F4C95D,stroke-width:2px;
    classDef process fill:#0C4A6E,color:#F8FAFC,stroke:#22D3EE,stroke-width:2px;
    classDef decision fill:#082F49,color:#F8FAFC,stroke:#38BDF8,stroke-width:2px;
    classDef result fill:#064E3B,color:#F8FAFC,stroke:#34D399,stroke-width:2px;
```

> This project reflects what I implemented and explored during my engineering work; it is not presented as years of production experience.

---

## `03 · Selected projects`

| Project | Context and contribution | Main technologies |
|---|---|---|
| **SkillWise** | E-learning platform with authentication, courses, quizzes, certificates, dashboards, messaging, and AI-assisted learning features. | React 19, Redux Toolkit, Node.js, Express, MongoDB, Tailwind CSS |
| **Scrumly** | Scrum collaboration platform with user roles, sprints, Kanban boards, burndown tracking, and notifications. | MERN stack, real-time features |
| **Real-Time Vehicle Tracking** | Layered C# application receiving and displaying vehicle data through Azure services. | C#, Azure IoT Hub, Event Hub, Azure SQL |
| **[QuetraTech Management System](https://github.com/Doua-Gannouni/PFE_Licence)** | Internal platform for quotations, invoices, projects, employees, payroll records, customers, after-sales communication, expenses, and dashboards. | React, Express, MySQL, Sequelize |

<p align="center">
  <a href="https://portfolio.doua-automation.xyz/"><img src="https://img.shields.io/badge/Explore_projects_on_my_portfolio-22D3EE?style=for-the-badge&logo=firefoxbrowser&logoColor=07111F" alt="Explore projects on portfolio" /></a>
</p>

---

## `04 · Technical toolkit`

These are technologies I have used in internships, engineering projects, academic work, or personal projects:

| Area | Technologies and practices |
|---|---|
| **Software development** | JavaScript, TypeScript, React, Redux Toolkit, Node.js, Express, Spring Boot, C#, Flutter, HTML, CSS, Tailwind CSS |
| **Manual testing** | Requirement analysis, functional testing, regression testing, integration testing, UI testing, test cases, defect reporting |
| **Test automation** | Playwright, Appium, Selenium, JUnit 5, Cucumber/Gherkin, Page Object Model, reusable Flows, Allure |
| **Data** | MySQL, MongoDB, Sequelize, Azure SQL |
| **Workflow & tracking** | Jira, TestLink, n8n |
| **DevOps & collaboration** | Git, GitHub, GitLab, GitLab CI/CD, Docker, Traefik, Cloudflare Tunnel |
| **Cloud exposure** | Azure IoT Hub, Azure Event Hub |

---

## `05 · Education and experience`

### Education

- **National Engineering Degree in Computer Engineering — 2026**  
  EPI Digital School / EPI Polytechnique de Sousse
- **National Bachelor's Degree in Information Technology — 2023**  
  Information Systems Development, ISET Mahdia

### Experience highlights

- **Webify Technology — Engineering final project:** web/mobile test automation, reporting, workflow orchestration, and QA agent proof of concept.
- **BeeCoders — Development internship:** contribution to the SkillWise MERN e-learning platform and its AI-assisted features.
- **QuetraTech — Bachelor's final project:** design and development of an internal management information system.
- **OMMP, Port of Sousse — Introductory internship:** first professional exposure through a static web project.

### Languages

- **Arabic:** native
- **French:** working proficiency
- **English:** B2, self-assessed

---

## `06 · Opportunities`

I am currently interested in full-time junior opportunities such as:

- **Junior QA Engineer / Software Tester**
- **Junior Test Automation Engineer**
- **Junior Software Engineer**
- **Junior Full-Stack Web Developer**

I am available for opportunities in **Tunisia, remote, or internationally**, and I am open to **relocation and positions offering visa sponsorship**.

---

## `07 · Contact`

<p align="center">
  <b>Have an opportunity, a project, or simply want to connect?</b><br/>
  I would be happy to discuss how I could contribute to your team.
</p>

<p align="center">
  <a href="https://portfolio.doua-automation.xyz/"><img src="https://img.shields.io/badge/Portfolio-Visit-22D3EE?style=for-the-badge&logo=firefoxbrowser&logoColor=07111F" alt="Visit portfolio" /></a>
  <a href="https://linkedin.com/in/gannounidoua"><img src="https://img.shields.io/badge/LinkedIn-Message_me-38BDF8?style=for-the-badge&logo=linkedin&logoColor=07111F" alt="Message on LinkedIn" /></a>
  <a href="mailto:gannounidoua09@gmail.com"><img src="https://img.shields.io/badge/Email-gannounidoua09%40gmail.com-F4C95D?style=for-the-badge&logo=gmail&logoColor=07111F" alt="Email Doua Gannouni" /></a>
</p>

<p align="center">
  <sub><code>build thoughtfully · test carefully · keep learning</code></sub>
</p>
![alt text](<header (2).svg>)