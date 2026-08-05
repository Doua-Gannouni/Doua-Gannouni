<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doua Gannouni · Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
            background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            padding: 2rem 1rem;
            color: #e2e8f0;
        }

        .card {
            max-width: 1000px;
            width: 100%;
            background: rgba(255, 255, 255, 0.04);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border-radius: 2.5rem;
            padding: 2.5rem 2rem;
            box-shadow: 0 30px 60px rgba(0, 0, 0, 0.6), 0 0 0 1px rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.06);
            transition: all 0.3s ease;
            animation: floatIn 1s ease-out;
        }

        @keyframes floatIn {
            0% { opacity: 0; transform: translateY(30px) scale(0.98); }
            100% { opacity: 1; transform: translateY(0) scale(1); }
        }

        /* --- typo & couleurs --- */
        h1, h2, h3, .gradient-text {
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 50%, #4facfe 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            display: inline-block;
        }

        .badge {
            display: inline-block;
            background: rgba(79, 172, 254, 0.15);
            backdrop-filter: blur(4px);
            padding: 0.3rem 1rem;
            border-radius: 40px;
            font-size: 0.75rem;
            font-weight: 600;
            letter-spacing: 0.03em;
            color: #a5b4fc;
            border: 1px solid rgba(79, 172, 254, 0.2);
            margin: 0.2rem 0.1rem;
            transition: all 0.2s;
        }

        .badge:hover {
            background: rgba(79, 172, 254, 0.3);
            border-color: #4facfe;
            transform: scale(1.03);
            color: #fff;
        }

        .badge i {
            margin-right: 0.4rem;
            color: #f093fb;
        }

        .pill {
            background: rgba(255, 255, 255, 0.04);
            border-radius: 100px;
            padding: 0.3rem 1.2rem;
            font-size: 0.7rem;
            font-weight: 600;
            letter-spacing: 0.05em;
            text-transform: uppercase;
            color: #94a3b8;
            border: 1px solid rgba(255, 255, 255, 0.04);
        }

        hr {
            border: none;
            height: 1px;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.08), transparent);
            margin: 2rem 0;
        }

        .section-title {
            display: flex;
            align-items: center;
            gap: 0.75rem;
            font-weight: 600;
            font-size: 1.3rem;
            letter-spacing: -0.02em;
            margin-bottom: 1rem;
        }

        .section-title i {
            font-size: 1.5rem;
            background: linear-gradient(135deg, #f093fb, #4facfe);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .grid-2 {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1.5rem;
        }

        @media (max-width: 700px) {
            .card { padding: 1.5rem 1rem; }
            .grid-2 { grid-template-columns: 1fr; }
        }

        .feature-box {
            background: rgba(255, 255, 255, 0.02);
            border-radius: 1.5rem;
            padding: 1.5rem;
            border: 1px solid rgba(255, 255, 255, 0.04);
            transition: all 0.25s;
        }

        .feature-box:hover {
            background: rgba(255, 255, 255, 0.05);
            border-color: rgba(79, 172, 254, 0.2);
            transform: translateY(-3px);
            box-shadow: 0 12px 30px -10px rgba(0, 0, 0, 0.5);
        }

        .icon-lg {
            font-size: 2.2rem;
            margin-right: 0.5rem;
            background: linear-gradient(135deg, #f093fb, #4facfe);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .tag {
            display: inline-block;
            background: rgba(255, 255, 255, 0.04);
            border-radius: 20px;
            padding: 0.2rem 0.8rem;
            font-size: 0.7rem;
            font-weight: 500;
            color: #cbd5e1;
            border: 1px solid rgba(255, 255, 255, 0.04);
            margin: 0.15rem 0.1rem;
            transition: 0.2s;
        }

        .tag i {
            margin-right: 0.3rem;
            color: #f093fb;
        }

        .tag:hover {
            background: rgba(79, 172, 254, 0.08);
            border-color: #4facfe33;
        }

        .step-flow {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem 1rem;
            justify-content: center;
            padding: 0.5rem 0;
        }

        .step {
            background: rgba(255, 255, 255, 0.03);
            padding: 0.3rem 1rem;
            border-radius: 40px;
            font-size: 0.8rem;
            font-weight: 500;
            color: #cbd5e1;
            border: 1px solid rgba(255, 255, 255, 0.04);
            display: flex;
            align-items: center;
            gap: 0.4rem;
            transition: 0.2s;
        }

        .step i {
            color: #f093fb;
        }

        .step:hover {
            background: rgba(79, 172, 254, 0.06);
            border-color: #4facfe33;
            transform: scale(1.02);
        }

        .quote {
            font-style: italic;
            color: #94a3b8;
            border-left: 3px solid #4facfe;
            padding-left: 1.2rem;
            margin: 1rem 0;
        }

        .footer-links a {
            color: #94a3b8;
            text-decoration: none;
            margin: 0 0.6rem;
            transition: 0.2s;
            font-weight: 500;
        }

        .footer-links a:hover {
            color: #f093fb;
            text-shadow: 0 0 12px #f093fb55;
        }

        .bounce-icon {
            display: inline-block;
            animation: pulseGlow 2.5s infinite;
        }

        @keyframes pulseGlow {
            0% { opacity: 0.7; transform: scale(1); }
            50% { opacity: 1; transform: scale(1.05); }
            100% { opacity: 0.7; transform: scale(1); }
        }

        .mermaid-placeholder {
            background: rgba(255, 255, 255, 0.02);
            border-radius: 1.5rem;
            padding: 1.5rem;
            border: 1px dashed rgba(255, 255, 255, 0.08);
            font-family: monospace;
            font-size: 0.75rem;
            line-height: 1.8;
            color: #94a3b8;
            overflow-x: auto;
            white-space: pre-wrap;
            word-break: break-word;
        }

        .mermaid-placeholder i {
            color: #4facfe;
            margin-right: 0.4rem;
        }

        .principle-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
            gap: 0.8rem;
            margin: 1rem 0;
        }

        .principle-item {
            background: rgba(255, 255, 255, 0.02);
            border-radius: 1rem;
            padding: 0.8rem 1rem;
            border: 1px solid rgba(255, 255, 255, 0.04);
            text-align: center;
            transition: 0.2s;
        }

        .principle-item:hover {
            background: rgba(79, 172, 254, 0.05);
            border-color: #4facfe33;
        }

        .principle-item i {
            font-size: 1.3rem;
            margin-bottom: 0.2rem;
            background: linear-gradient(135deg, #f093fb, #4facfe);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .principle-item strong {
            display: block;
            font-weight: 600;
        }
        .principle-item span {
            font-size: 0.7rem;
            color: #94a3b8;
        }

        /* timeline simple */
        .timeline-item {
            display: flex;
            gap: 1rem;
            padding: 0.6rem 0;
            border-bottom: 1px solid rgba(255, 255, 255, 0.03);
        }
        .timeline-item:last-child { border-bottom: none; }
        .timeline-year {
            min-width: 70px;
            font-weight: 600;
            color: #a5b4fc;
        }
        .timeline-content {
            color: #cbd5e1;
        }
        .timeline-content strong {
            color: #e2e8f0;
        }

        .badge-group {
            display: flex;
            flex-wrap: wrap;
            gap: 0.3rem;
        }

        .blob {
            position: absolute;
            width: 300px;
            height: 300px;
            border-radius: 50%;
            filter: blur(120px);
            opacity: 0.15;
            z-index: -1;
            pointer-events: none;
        }
        .card { position: relative; overflow: hidden; }
        .blob1 { background: #f093fb; top: -120px; right: -120px; }
        .blob2 { background: #4facfe; bottom: -120px; left: -120px; }

        /* scrollbar */
        ::-webkit-scrollbar { width: 4px; }
        ::-webkit-scrollbar-track { background: transparent; }
        ::-webkit-scrollbar-thumb { background: #4facfe66; border-radius: 10px; }
    </style>
</head>
<body>
    <div class="card">
        <!-- blobs décoratifs -->
        <div class="blob blob1"></div>
        <div class="blob blob2"></div>

        <!-- HEADER -->
        <div align="center" style="margin-bottom: 1.5rem;">
            <div style="display: flex; align-items: center; gap: 0.6rem; flex-wrap: wrap; justify-content: center;">
                <span class="pill"><i class="fa-regular fa-circle-check" style="color:#4facfe;"></i> COMPUTER ENGINEER</span>
                <span class="pill"><i class="fa-regular fa-code" style="color:#f093fb;"></i> SOFTWARE ENGINEERING</span>
            </div>
            <h1 style="font-size: 2.8rem; font-weight: 800; letter-spacing: -0.03em; margin: 0.5rem 0 0.2rem;">
                Doua Gannouni
            </h1>
            <div style="display: flex; gap: 0.8rem; flex-wrap: wrap; justify-content: center; font-weight: 400; color: #94a3b8; font-size: 1rem;">
                <span><i class="fa-solid fa-laptop-code" style="color:#4facfe;"></i> Full-Stack</span>
                <span><i class="fa-solid fa-vial" style="color:#f093fb;"></i> Software Testing</span>
                <span><i class="fa-solid fa-robot" style="color:#a78bfa;"></i> QA Automation</span>
            </div>
            <div class="quote" style="max-width: 600px; margin: 1rem auto; text-align: center;">
                <i class="fa-solid fa-quote-left" style="color:#4facfe66;"></i>
                Building reliable web solutions through clean development, systematic testing and intelligent automation.
            </div>
            <div class="footer-links" style="margin-top: 0.3rem;">
                <a href="#"><i class="fa-regular fa-folder-open"></i> Portfolio</a>
                <a href="#"><i class="fa-brands fa-linkedin"></i> LinkedIn</a>
                <a href="#"><i class="fa-regular fa-envelope"></i> Email</a>
            </div>
        </div>

        <hr>

        <!-- PROFILE -->
        <div>
            <div class="section-title"><i class="fa-regular fa-user"></i> Profile</div>
            <p style="color:#cbd5e1; line-height:1.7;">
                I am Doua Gannouni, a Computer Engineer specialized in Software Engineering.
                My experience comes from internships and academic projects in full-stack web development, software testing and QA automation.
                I mainly work with the MERN stack and modern testing tools, while exploring practical applications of Artificial Intelligence, workflow automation and Big Data.
                I approach software from two complementary perspectives: <strong style="color:#f093fb;">development</strong> and <strong style="color:#4facfe;">quality</strong>.
            </p>
        </div>

        <hr>

        <!-- ENGINEERING FOCUS -->
        <div>
            <div class="section-title"><i class="fa-regular fa-compass"></i> Engineering Focus</div>
            <div class="grid-2">
                <div class="feature-box">
                    <div style="display:flex; align-items:center; gap:0.5rem; margin-bottom:0.5rem;">
                        <span style="font-size:2rem; background:linear-gradient(135deg,#f093fb,#f5576c); -webkit-background-clip:text; -webkit-text-fill-color:transparent;">01</span>
                        <span style="font-weight:700; font-size:1.2rem;">BUILD</span>
                    </div>
                    <ul style="list-style:none; color:#94a3b8; font-size:0.9rem; line-height:1.8;">
                        <li><i class="fa-regular fa-circle-check" style="color:#4facfe; width:1.2rem;"></i> Responsive web interfaces</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#4facfe; width:1.2rem;"></i> REST APIs and authentication</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#4facfe; width:1.2rem;"></i> Database-driven applications</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#4facfe; width:1.2rem;"></i> Maintainable architectures</li>
                    </ul>
                </div>
                <div class="feature-box">
                    <div style="display:flex; align-items:center; gap:0.5rem; margin-bottom:0.5rem;">
                        <span style="font-size:2rem; background:linear-gradient(135deg,#4facfe,#43e97b); -webkit-background-clip:text; -webkit-text-fill-color:transparent;">02</span>
                        <span style="font-weight:700; font-size:1.2rem;">TEST</span>
                    </div>
                    <ul style="list-style:none; color:#94a3b8; font-size:0.9rem; line-height:1.8;">
                        <li><i class="fa-regular fa-circle-check" style="color:#43e97b; width:1.2rem;"></i> Functional and regression testing</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#43e97b; width:1.2rem;"></i> End-to-end validation</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#43e97b; width:1.2rem;"></i> Defect tracking and reporting</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#43e97b; width:1.2rem;"></i> Evidence-based quality</li>
                    </ul>
                </div>
                <div class="feature-box" style="grid-column: 1 / -1;">
                    <div style="display:flex; align-items:center; gap:0.5rem; margin-bottom:0.5rem;">
                        <span style="font-size:2rem; background:linear-gradient(135deg,#f093fb,#4facfe); -webkit-background-clip:text; -webkit-text-fill-color:transparent;">03</span>
                        <span style="font-weight:700; font-size:1.2rem;">AUTOMATE</span>
                    </div>
                    <ul style="list-style:none; color:#94a3b8; font-size:0.9rem; line-height:1.8; display:flex; flex-wrap:wrap; gap:0.5rem 1.5rem;">
                        <li><i class="fa-regular fa-circle-check" style="color:#a78bfa;"></i> Reusable automated test suites</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#a78bfa;"></i> BDD and Page Object Model</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#a78bfa;"></i> CI/CD and workflow orchestration</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#a78bfa;"></i> AI-assisted QA processes</li>
                    </ul>
                </div>
            </div>
        </div>

        <hr>

        <!-- TOOLBOX -->
        <div>
            <div class="section-title"><i class="fa-regular fa-screwdriver-wrench"></i> Technical Toolbox</div>
            <details open style="margin-bottom:0.8rem;">
                <summary style="font-weight:600; cursor:pointer; color:#e2e8f0;"><i class="fa-regular fa-laptop-code" style="color:#f093fb;"></i> Full-Stack Development</summary>
                <div class="badge-group" style="margin-top:0.6rem;">
                    <span class="badge"><i class="fa-brands fa-react"></i> React.js</span>
                    <span class="badge"><i class="fa-brands fa-js"></i> JavaScript</span>
                    <span class="badge"><i class="fa-brands fa-js"></i> TypeScript</span>
                    <span class="badge"><i class="fa-brands fa-node"></i> Node.js</span>
                    <span class="badge"><i class="fa-regular fa-server"></i> Express.js</span>
                    <span class="badge"><i class="fa-regular fa-database"></i> MongoDB</span>
                    <span class="badge"><i class="fa-regular fa-database"></i> MySQL</span>
                    <span class="badge"><i class="fa-brands fa-laravel"></i> Laravel</span>
                    <span class="badge"><i class="fa-brands fa-php"></i> PHP</span>
                    <span class="badge"><i class="fa-regular fa-code"></i> REST APIs</span>
                    <span class="badge"><i class="fa-brands fa-html5"></i> HTML5</span>
                    <span class="badge"><i class="fa-brands fa-css3-alt"></i> CSS3</span>
                    <span class="badge"><i class="fa-brands fa-tailwind"></i> Tailwind CSS</span>
                    <span class="badge"><i class="fa-brands fa-bootstrap"></i> Bootstrap</span>
                </div>
            </details>

            <details open style="margin-bottom:0.8rem;">
                <summary style="font-weight:600; cursor:pointer; color:#e2e8f0;"><i class="fa-regular fa-flask" style="color:#43e97b;"></i> Software Testing & QA Automation</summary>
                <div class="badge-group" style="margin-top:0.6rem;">
                    <span class="badge"><i class="fa-regular fa-play"></i> Playwright</span>
                    <span class="badge"><i class="fa-regular fa-flask"></i> Selenium</span>
                    <span class="badge"><i class="fa-regular fa-mobile-screen"></i> Appium</span>
                    <span class="badge"><i class="fa-regular fa-file-lines"></i> BDD / Gherkin</span>
                    <span class="badge"><i class="fa-regular fa-layer-group"></i> Page Object Model</span>
                    <span class="badge"><i class="fa-regular fa-vial"></i> Functional Testing</span>
                    <span class="badge"><i class="fa-regular fa-rotate"></i> Regression Testing</span>
                    <span class="badge"><i class="fa-regular fa-arrows-spin"></i> End-to-End Testing</span>
                    <span class="badge"><i class="fa-regular fa-chart-bar"></i> Allure Report</span>
                    <span class="badge"><i class="fa-brands fa-jira"></i> Jira</span>
                </div>
            </details>

            <details>
                <summary style="font-weight:600; cursor:pointer; color:#e2e8f0;"><i class="fa-regular fa-gear" style="color:#a78bfa;"></i> DevOps, Automation & AI</summary>
                <div class="badge-group" style="margin-top:0.6rem;">
                    <span class="badge"><i class="fa-brands fa-git-alt"></i> Git</span>
                    <span class="badge"><i class="fa-brands fa-github"></i> GitHub</span>
                    <span class="badge"><i class="fa-brands fa-gitlab"></i> GitLab CI/CD</span>
                    <span class="badge"><i class="fa-regular fa-cube"></i> Docker</span>
                    <span class="badge"><i class="fa-regular fa-bolt"></i> Postman</span>
                    <span class="badge"><i class="fa-regular fa-diagram-project"></i> n8n</span>
                    <span class="badge"><i class="fa-regular fa-brain"></i> OpenAI API</span>
                    <span class="badge"><i class="fa-regular fa-brain"></i> Gemini API</span>
                    <span class="badge"><i class="fa-brands fa-python"></i> Python</span>
                </div>
            </details>
        </div>

        <hr>

        <!-- FEATURED PROJECT -->
        <div>
            <div class="section-title"><i class="fa-regular fa-rocket"></i> Featured Engineering Project</div>
            <div style="background:rgba(255,255,255,0.02); border-radius:1.5rem; padding:1.5rem; border:1px solid rgba(255,255,255,0.04);">
                <h3 style="font-size:1.3rem; margin-bottom:0.3rem;">Intelligent QA Automation Ecosystem</h3>
                <p style="color:#94a3b8; margin-bottom:1rem;">For my final-year engineering project, I designed a reusable QA automation solution connecting issue tracking, workflow orchestration, automated execution and reporting.</p>

                <!-- mermaid-like diagram -->
                <div class="mermaid-placeholder">
                    <i class="fa-regular fa-sitemap"></i> flowchart LR
                    A["Jira Ticket<br/>Issue context"] --> B["n8n Workflow<br/>Orchestration"]
                    B --> C["AI QA Agent<br/>Ticket analysis"]
                    C --> D{"Select validation path"}

                    D -->|Web| E["Playwright + TypeScript"]
                    D -->|Application| F["Appium"]

                    E --> G["BDD / POM Test Execution"]
                    F --> G

                    G --> H{"Test verdict"}
                    H -->|Passed| I["Jira feedback<br/>Validation result"]
                    H -->|Failed| J["Allure evidence<br/>Logs and screenshots"]

                    J --> K["Defect update"]
                    K --> I
                </div>

                <div style="margin-top:1.2rem;">
                    <strong style="color:#e2e8f0;">Key Contributions</strong>
                    <div style="display:flex; flex-wrap:wrap; gap:0.5rem 1rem; margin-top:0.4rem; color:#94a3b8; font-size:0.9rem;">
                        <span><i class="fa-regular fa-circle-check" style="color:#4facfe;"></i> Automated web testing with Playwright and TypeScript</span>
                        <span><i class="fa-regular fa-circle-check" style="color:#4facfe;"></i> Automated application testing with Appium</span>
                        <span><i class="fa-regular fa-circle-check" style="color:#4facfe;"></i> Reusable architecture based on BDD/Gherkin and Page Object Model</span>
                        <span><i class="fa-regular fa-circle-check" style="color:#4facfe;"></i> Test evidence and reporting with Allure</span>
                        <span><i class="fa-regular fa-circle-check" style="color:#4facfe;"></i> Issue tracking and automated feedback through Jira</span>
                        <span><i class="fa-regular fa-circle-check" style="color:#4facfe;"></i> Workflow orchestration with n8n</span>
                        <span><i class="fa-regular fa-circle-check" style="color:#4facfe;"></i> Containerization and CI/CD using Docker and GitLab</span>
                        <span><i class="fa-regular fa-circle-check" style="color:#4facfe;"></i> An AI-assisted QA agent for ticket analysis and automated validation</span>
                    </div>
                </div>
            </div>
        </div>

        <hr>

        <!-- EXPERIENCE SNAPSHOT -->
        <div>
            <div class="section-title"><i class="fa-regular fa-briefcase"></i> Experience Snapshot</div>
            <div>
                <div class="timeline-item">
                    <div class="timeline-year">2026</div>
                    <div class="timeline-content"><strong>QA Automation & AI Engineering Intern</strong> · Webify Technology — Intelligent automated testing ecosystem using Playwright, Appium, Jira, Allure, n8n, Docker and AI</div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-year">2024</div>
                    <div class="timeline-content"><strong>Full-Stack MERN Developer Intern</strong> · BeeCoders — E-learning platform with REST APIs, authentication, notifications and AI-powered features</div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-year">2023</div>
                    <div class="timeline-content"><strong>Full-Stack MERN Developer</strong> · Final-Year Project — Business information system for clients, projects, employees, invoices, documents and dashboards</div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-year">2022</div>
                    <div class="timeline-content"><strong>Laravel Web Developer Intern</strong> — Development and testing of modules for a real-estate platform</div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-year">2021</div>
                    <div class="timeline-content"><strong>Front-End Developer Intern</strong> — Responsive website for maritime services</div>
                </div>
            </div>
        </div>

        <hr>

        <!-- SELECTED PROJECT AREAS -->
        <div>
            <div class="section-title"><i class="fa-regular fa-folder-tree"></i> Selected Project Areas</div>
            <div class="grid-2">
                <div class="feature-box">
                    <i class="fa-regular fa-layer-group icon-lg"></i>
                    <h4 style="color:#e2e8f0; margin:0.2rem 0;">Full-Stack Platforms</h4>
                    <ul style="list-style:none; color:#94a3b8; font-size:0.9rem; line-height:1.9;">
                        <li><i class="fa-regular fa-circle-check" style="color:#4facfe;"></i> Business information systems</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#4facfe;"></i> E-learning platforms</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#4facfe;"></i> Agile project management</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#4facfe;"></i> Authentication and roles</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#4facfe;"></i> Dashboards and reporting</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#4facfe;"></i> Real-time application features</li>
                    </ul>
                </div>
                <div class="feature-box">
                    <i class="fa-regular fa-vial icon-lg"></i>
                    <h4 style="color:#e2e8f0; margin:0.2rem 0;">Quality Engineering</h4>
                    <ul style="list-style:none; color:#94a3b8; font-size:0.9rem; line-height:1.9;">
                        <li><i class="fa-regular fa-circle-check" style="color:#43e97b;"></i> Functional test design</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#43e97b;"></i> End-to-end automation</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#43e97b;"></i> BDD test architecture</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#43e97b;"></i> Automated reporting</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#43e97b;"></i> Jira-integrated workflows</li>
                        <li><i class="fa-regular fa-circle-check" style="color:#43e97b;"></i> AI-assisted validation</li>
                    </ul>
                </div>
            </div>
        </div>

        <hr>

        <!-- APPROACH -->
        <div>
            <div class="section-title"><i class="fa-regular fa-arrows-spin"></i> How I Approach Software</div>
            <div class="step-flow">
                <span class="step"><i class="fa-regular fa-eye"></i> UNDERSTAND</span>
                <span class="step"><i class="fa-regular fa-pen-ruler"></i> DESIGN</span>
                <span class="step"><i class="fa-regular fa-hammer"></i> BUILD</span>
                <span class="step"><i class="fa-regular fa-flask"></i> TEST</span>
                <span class="step"><i class="fa-regular fa-robot"></i> AUTOMATE</span>
                <span class="step"><i class="fa-regular fa-arrow-up"></i> IMPROVE</span>
            </div>

            <div class="principle-grid">
                <div class="principle-item">
                    <i class="fa-regular fa-lightbulb"></i>
                    <strong>Clarity</strong>
                    <span>Understand the real need before choosing a technical solution</span>
                </div>
                <div class="principle-item">
                    <i class="fa-regular fa-shield"></i>
                    <strong>Reliability</strong>
                    <span>Validate behavior instead of relying only on implementation</span>
                </div>
                <div class="principle-item">
                    <i class="fa-regular fa-boxes"></i>
                    <strong>Maintainability</strong>
                    <span>Build reusable structures that are easier to evolve</span>
                </div>
                <div class="principle-item">
                    <i class="fa-regular fa-gear"></i>
                    <strong>Automation</strong>
                    <span>Reduce repetitive work while preserving traceability</span>
                </div>
                <div class="principle-item">
                    <i class="fa-regular fa-graduation-cap"></i>
                    <strong>Learning</strong>
                    <span>Improve continuously through feedback and experimentation</span>
                </div>
            </div>
        </div>

        <hr>

        <!-- PROFESSIONAL DIRECTION -->
        <div>
            <div class="section-title"><i class="fa-regular fa-globe"></i> Professional Direction</div>
            <p style="color:#cbd5e1;">
                I am open to junior and graduate opportunities worldwide involving:
            </p>
            <div style="display:flex; flex-wrap:wrap; gap:0.4rem 0.8rem; margin:0.8rem 0;">
                <span class="badge"><i class="fa-regular fa-code"></i> Full-Stack Web Development</span>
                <span class="badge"><i class="fa-regular fa-flask"></i> Software Testing</span>
                <span class="badge"><i class="fa-regular fa-robot"></i> QA Automation</span>
                <span class="badge"><i class="fa-regular fa-diagram-project"></i> Intelligent workflow automation</span>
                <span class="badge"><i class="fa-regular fa-brain"></i> AI-assisted software solutions</span>
            </div>
            <p style="color:#94a3b8; font-size:0.9rem;">
                I value clear communication, continuous learning, maintainable code and evidence-based quality.
            </p>
        </div>

        <hr>

        <!-- FOOTER -->
        <div align="center" style="margin-top:0.5rem;">
            <div style="font-size:1.2rem; font-weight:400; color:#e2e8f0;">Let’s build reliable software together.</div>
            <div class="footer-links" style="margin:0.6rem 0;">
                <a href="#"><i class="fa-regular fa-folder-open"></i> Explore my portfolio</a>
                <a href="#"><i class="fa-brands fa-linkedin"></i> Connect with me on LinkedIn</a>
                <a href="#"><i class="fa-regular fa-envelope"></i> Contact me by email</a>
            </div>
            <div style="margin-top:0.6rem;">
                <span class="pill"><i class="fa-regular fa-rocket" style="color:#f093fb;"></i> BUILD THOUGHTFULLY · TEST CAREFULLY · IMPROVE CONTINUOUSLY</span>
            </div>
            <div style="margin-top:1.2rem; font-size:0.7rem; color:#475569;">
                <i class="fa-regular fa-copyright"></i> 2026 Doua Gannouni · Computer Engineer
            </div>
        </div>
    </div>
</body>
</html>
