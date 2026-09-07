<!-- DOUA GANNOUNI · GitHub Profile README -->

<p align="center">
  <img src="./header.svg" width="100%" alt="Doua Gannouni — Software Engineer, QA Automation and Full-Stack Development" />
</p>

<p align="center">
  <a href="https://portfolio.doua-automation.xyz/"><img src="https://img.shields.io/badge/Portfolio-Explore-22D3EE?style=for-the-badge&logo=firefoxbrowser&logoColor=07111F&labelColor=0B172A" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/gannounidoua"><img src="https://img.shields.io/badge/LinkedIn-Connect-38BDF8?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0B172A" alt="LinkedIn" /></a>
  <a href="mailto:gannounidoua09@gmail.com"><img src="https://img.shields.io/badge/Email-Let's_talk-F4C95D?style=for-the-badge&logo=gmail&logoColor=07111F&labelColor=0B172A" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Monastir-Tunisia-0B172A?style=flat-square&logo=googlemaps&logoColor=F4C95D" alt="Monastir, Tunisia" />
  <img src="https://img.shields.io/badge/Open_to-worldwide_opportunities-0B172A?style=flat-square&logo=airplayvideo&logoColor=22D3EE" alt="Open to worldwide opportunities" />
  <img src="https://img.shields.io/badge/Relocation-Available-0B172A?style=flat-square&logo=googleearth&logoColor=22D3EE" alt="Relocation available" />
</p>

<table>
<tr>
<td width="72%" valign="top">
<h2><code>whoami</code></h2>
<pre><code>const doua = {
  role: "Software Engineer",
  focus: ["QA Automation", "Full-Stack Development", "AI-assisted Testing"],
  builds: ["MERN applications", "REST APIs", "maintainable architectures"],
  tests: ["Web E2E", "Mobile", "BDD", "Regression"],
  automates: ["n8n workflows", "QA agents", "CI/CD pipelines"],
  languages: ["Arabic", "French", "English"],
  status: "Open to opportunities worldwide",
};</code></pre>
</td>
<td width="28%" align="center" valign="middle">
  <img src="./doua-robot-avatar.png" width="210" alt="Doua Gannouni — robotic portrait" />
</td>
</tr>
</table>

I work where software development meets quality engineering: building useful products, designing reliable tests, and automating the path from change to verdict.

01 · Featured engineering project

Autonomous QA Pipeline

For my engineering project, I designed an intelligent QA workflow that connects Jira, n8n, an AI QA agent, web and mobile automation, Allure reporting, and isolated CI/CD environments.

A Jira ticket triggers the workflow → the agent analyses what should be checked → automated tests run on the appropriate platform → evidence and the final verdict are written back to Jira.

flowchart LR
    A["Jira Ticket"]:::source --> B["n8n Orchestrator"]:::process
    B --> C["AI QA Agent<br/>reason · act · observe"]:::process
    C --> D{"Target?"}:::decision
    D -->|Web| E["Playwright + TypeScript"]:::process
    D -->|Mobile| F["Appium"]:::process
    E --> G["BDD · POM · Allure"]:::process
    F --> G
    G --> H{"Verdict"}:::decision
    H -->|PASS| I["Ticket validated"]:::pass
    H -->|FAIL| J["Evidence attached<br/>Defect reopened"]:::fail
    J -.-> A

    classDef source fill:#0B172A,color:#F8FAFC,stroke:#F4C95D,stroke-width:2px;
    classDef process fill:#0C4A6E,color:#F8FAFC,stroke:#22D3EE,stroke-width:2px;
    classDef decision fill:#082F49,color:#F8FAFC,stroke:#38BDF8,stroke-width:2px;
    classDef pass fill:#064E3B,color:#F8FAFC,stroke:#34D399,stroke-width:2px;
    classDef fail fill:#4C1D24,color:#F8FAFC,stroke:#FB7185,stroke-width:2px;

<details>
<summary><b>What makes this project technically interesting</b></summary>
<br/>

A ReAct-inspired loop lets the agent reason, act, observe the application, and choose the next test action.

Guardrails reduce false passes when the flow encounters blockers such as CAPTCHA or OTP screens.

Playwright covers the web application, while Appium covers the Android mobile application.

BDD, Page Objects, Flows, and Allure keep test intent, implementation, and evidence structured.

The CI/CD architecture supports isolated preview environments with Docker, dynamic routing, and secure tunnels.

n8n coordinates ticket generation, agent validation, reporting, and sandbox lifecycle workflows.

</details>

02 · Technical toolkit

<table>
<tr>
<td width="18%"><b>Build</b></td>
<td><code>React</code> <code>TypeScript</code> <code>JavaScript</code> <code>Node.js</code> <code>Express</code> <code>Spring Boot</code> <code>MongoDB</code> <code>MySQL</code> <code>Tailwind CSS</code></td>
</tr>
<tr>
<td><b>Test</b></td>
<td><code>Playwright</code> <code>Appium</code> <code>Selenium</code> <code>JUnit 5</code> <code>Cucumber</code> <code>Postman</code> <code>Allure</code> <code>Jira</code></td>
</tr>
<tr>
<td><b>Automate</b></td>
<td><code>n8n</code> <code>Docker</code> <code>GitLab CI/CD</code> <code>GitHub</code> <code>AI agents</code> <code>Traefik</code> <code>Cloudflare Tunnel</code></td>
</tr>
</table>

03 · Engineering approach

flowchart LR
    U(("Understand")):::step --> D(("Design")):::step --> B(("Build")):::step --> T(("Test")):::step --> I(("Improve")):::step
    I -.->|iterate| U

    classDef step fill:#0B172A,color:#E6F7FF,stroke:#22D3EE,stroke-width:2px;

Understand the why · design for maintainability · build with purpose · prove quality through automation · learn and improve.

04 · Let's work together

<p align="center">
  <b>Have an opportunity, a project, or simply want to connect?</b><br/>
  I am open to junior software engineering and QA automation opportunities in Tunisia and internationally.
</p>

<p align="center">
  <a href="https://portfolio.doua-automation.xyz/"><img src="https://img.shields.io/badge/View_my_portfolio-22D3EE?style=for-the-badge&logo=firefoxbrowser&logoColor=07111F" alt="View portfolio" /></a>
  <a href="https://linkedin.com/in/gannounidoua"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-38BDF8?style=for-the-badge&logo=linkedin&logoColor=07111F" alt="Connect on LinkedIn" /></a>
  <a href="mailto:gannounidoua09@gmail.com"><img src="https://img.shields.io/badge/Send_an_email-F4C95D?style=for-the-badge&logo=gmail&logoColor=07111F" alt="Send an email" /></a>
</p>

<p align="center">
  <sub><code>build thoughtfully · test intelligently · improve continuously</code></sub>
</p>
