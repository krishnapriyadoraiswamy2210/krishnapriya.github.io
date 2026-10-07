<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Krishnapriya Doraiswamy | Data Analyst</title>

    <meta name="description"
          content="Krishnapriya Doraiswamy - Data Analyst specialising in SQL, Python, Power BI, Tableau, Snowflake and data analytics.">

    <link rel="stylesheet"
          href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

    <style>

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Inter, Arial, sans-serif;
            background: #f8fafc;
            color: #172033;
            line-height: 1.6;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* =========================
           NAVIGATION
        ========================= */

        nav {
            position: sticky;
            top: 0;
            z-index: 1000;
            background: rgba(255,255,255,0.94);
            backdrop-filter: blur(12px);
            border-bottom: 1px solid #e5e7eb;
        }

        .nav-container {
            max-width: 1150px;
            margin: auto;
            padding: 18px 25px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 21px;
            font-weight: 700;
        }

        .logo span {
            color: #2563eb;
        }

        .nav-links {
            display: flex;
            gap: 30px;
            list-style: none;
            font-size: 14px;
            color: #475569;
        }

        .nav-links a:hover {
            color: #2563eb;
        }

        /* =========================
           GENERAL
        ========================= */

        .container {
            width: 100%;
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 5vw;
        }

       section {
            width: 100%;
            padding: 90px 5vw;
        }

        .section-label {
            color: #2563eb;
            font-size: 13px;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            margin-bottom: 10px;
        }

        .section-title {
            font-size: 34px;
            margin-bottom: 15px;
        }

        .section-description {
            color: #64748b;
            max-width: 700px;
            margin-bottom: 40px;
        }

        /* =========================
           HERO
        ========================= */

        .hero {
            background: white;
            padding: 100px 0 80px;
        }

        .hero-grid {
            width: 100%;
            display: grid;
            grid-template-columns: 1.5fr 0.8fr;
            gap: 8vw;
            align-items: center;
        }

        .hero-tag {
            display: inline-block;
            background: #eff6ff;
            color: #2563eb;
            padding: 7px 14px;
            border-radius: 30px;
            font-size: 13px;
            font-weight: 600;
            margin-bottom: 20px;
        }

        .hero h1 {
            font-size: 56px;
            line-height: 1.08;
            letter-spacing: -2px;
            margin-bottom: 22px;
        }

        .hero h1 span {
            color: #2563eb;
        }

        .hero-text {
            font-size: 18px;
            color: #64748b;
            max-width: 680px;
            margin-bottom: 30px;
        }

        .buttons {
            display: flex;
            gap: 14px;
            flex-wrap: wrap;
        }

        .btn {
            padding: 12px 20px;
            border-radius: 8px;
            font-weight: 600;
            font-size: 14px;
            transition: 0.2s;
        }

        .btn-primary {
            background: #2563eb;
            color: white;
        }

        .btn-primary:hover {
            background: #1d4ed8;
        }

        .btn-secondary {
            border: 1px solid #d1d5db;
            background: white;
        }

        .btn-secondary:hover {
            border-color: #2563eb;
            color: #2563eb;
        }

        /* =========================
           HERO CARD
        ========================= */

        .hero-card {
            background: #0f172a;
            border-radius: 20px;
            padding: 30px;
            color: white;
            box-shadow: 0 20px 50px rgba(15,23,42,0.15);
        }

        .hero-card-title {
            font-size: 14px;
            color: #94a3b8;
            margin-bottom: 20px;
        }

        .data-flow {
            display: flex;
            flex-direction: column;
            gap: 14px;
        }

        .flow-item {
            background: #1e293b;
            border-radius: 10px;
            padding: 15px;
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .flow-icon {
            width: 35px;
            height: 35px;
            border-radius: 8px;
            background: #2563eb;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .flow-arrow {
            text-align: center;
            color: #64748b;
        }

        /* =========================
           STATS
        ========================= */

        .stats {
            background: #f1f5f9;
            padding: 25px 0;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
        }

        .stat {
            text-align: center;
            padding: 15px;
        }

        .stat h3 {
            font-size: 28px;
            color: #2563eb;
        }

        .stat p {
            color: #64748b;
            font-size: 13px;
        }

        /* =========================
           ABOUT
        ========================= */

        .about-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            align-items: center;
        }

        .about-text p {
            margin-bottom: 18px;
            color: #64748b;
        }

        .about-box {
            background: white;
            border: 1px solid #e5e7eb;
            border-radius: 16px;
            padding: 30px;
        }

        .about-box h3 {
            margin-bottom: 20px;
        }

        .about-list {
            list-style: none;
        }

        .about-list li {
            margin-bottom: 15px;
            color: #64748b;
        }

        .about-list i {
            color: #2563eb;
            margin-right: 10px;
        }

        /* =========================
           WORKFLOW
        ========================= */

        .workflow {
            background: white;
        }

        .workflow-grid {
            display: grid;
            grid-template-columns: repeat(4,1fr);
            gap: 20px;
        }

        .workflow-card {
            border: 1px solid #e5e7eb;
            border-radius: 14px;
            padding: 25px;
            background: #fff;
        }

        .workflow-number {
            color: #2563eb;
            font-size: 13px;
            font-weight: 700;
        }

        .workflow-card h3 {
            margin: 12px 0;
            font-size: 18px;
        }

        .workflow-card p {
            color: #64748b;
            font-size: 14px;
        }

        /* =========================
           PROJECTS
        ========================= */

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(2,1fr);
            gap: 25px;
        }

        .project {
            background: white;
            border: 1px solid #e5e7eb;
            border-radius: 16px;
            overflow: hidden;
            transition: 0.25s;
        }

        .project:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 35px rgba(15,23,42,0.08);
        }

        .project-image {
            height: 190px;
            background: linear-gradient(135deg,#dbeafe,#eff6ff);
            display: flex;
            align-items: center;
            justify-content: center;
            color: #2563eb;
            font-size: 50px;
        }

        .project-content {
            padding: 25px;
        }

        .project-tag {
            display: inline-block;
            font-size: 11px;
            background: #eff6ff;
            color: #2563eb;
            padding: 5px 9px;
            border-radius: 20px;
            margin-bottom: 12px;
            font-weight: 600;
        }

        .project h3 {
            font-size: 21px;
            margin-bottom: 10px;
        }

        .project p {
            color: #64748b;
            font-size: 14px;
            margin-bottom: 18px;
        }

        .tech {
            display: flex;
            flex-wrap: wrap;
            gap: 7px;
            margin-bottom: 20px;
        }

        .tech span {
            background: #f1f5f9;
            padding: 5px 9px;
            border-radius: 5px;
            font-size: 11px;
            color: #475569;
        }

        .project-links {
            display: flex;
            gap: 15px;
            color: #2563eb;
            font-size: 13px;
            font-weight: 600;
        }

        /* =========================
           SKILLS
        ========================= */

        .skills {
            background: white;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(3,1fr);
            gap: 25px;
        }

        .skill-card {
            border: 1px solid #e5e7eb;
            border-radius: 14px;
            padding: 25px;
        }

        .skill-card h3 {
            margin-bottom: 15px;
            font-size: 18px;
        }

        .skill-card p {
            color: #64748b;
            font-size: 14px;
        }

        /* =========================
           CONTACT
        ========================= */

        .contact {
            background: #0f172a;
            color: white;
            text-align: center;
        }

        .contact .section-label {
            color: #60a5fa;
        }

        .contact h2 {
            font-size: 38px;
            margin-bottom: 15px;
        }

        .contact p {
            color: #94a3b8;
            max-width: 600px;
            margin: 0 auto 30px;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .social-links a {
            width: 45px;
            height: 45px;
            border: 1px solid #334155;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            transition: 0.2s;
        }

        .social-links a:hover {
            background: #2563eb;
            border-color: #2563eb;
        }

        /* =========================
           FOOTER
        ========================= */

        footer {
            background: #020617;
            color: #64748b;
            text-align: center;
            padding: 20px;
            font-size: 12px;
        }

        /* =========================
           MOBILE
        ========================= */

        @media (max-width: 800px) {

            .nav-links {
                display: none;
            }

            .hero-grid,
            .about-grid {
                grid-template-columns: 1fr;
            }

            .hero h1 {
                font-size: 42px;
            }

            .stats-grid {
                grid-template-columns: repeat(2,1fr);
            }

            .workflow-grid,
            .skills-grid {
                grid-template-columns: 1fr 1fr;
            }

            .projects-grid {
                grid-template-columns: 1fr;
            }
        }

        @media (max-width: 550px) {

            section {
                padding: 65px 0;
            }

            .workflow-grid,
            .skills-grid {
                grid-template-columns: 1fr;
            }

            .hero h1 {
                font-size: 36px;
            }

            .stats-grid {
                grid-template-columns: 1fr 1fr;
            }
        }

    </style>
</head>

<body>


<!-- =========================
     NAVIGATION
========================= -->

<nav>
    <div class="nav-container">

        <div class="logo">
            Krishnapriya<span>.</span>
        </div>

        <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#approach">Approach</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>

    </div>
</nav>


<!-- =========================
     HERO
========================= -->

<section class="hero">

    <div class="container">

        <div class="hero-grid">

            <div>

                <div class="hero-tag">
                    Data Analyst • BI • Analytics
                </div>

                <h1>
                    Turning data into
                    <span>clear business decisions.</span>
                </h1>

                <p class="hero-text">
                    I'm Krishnapriya, a Data Analyst with 5+ years of
                    experience working across analytics, business intelligence,
                    data services and product analytics.
                </p>

                <div class="buttons">

                    <a href="#projects"
                       class="btn btn-primary">
                        View My Projects
                    </a>

                    <a href="Krishnapriya_Doraiswamy_CV.pdf"
                       class="btn btn-secondary">
                        Download CV
                    </a>

                    <a href="https://github.com/krishnapriyadoraiswamy2210"
                       target="_blank"
                       class="btn btn-secondary">
                        GitHub
                    </a>

                </div>

            </div>


            <!-- DATA FLOW CARD -->

            <div class="hero-card">

                <div class="hero-card-title">
                    MY ANALYTICS WORKFLOW
                </div>

                <div class="data-flow">

                    <div class="flow-item">
                        <div class="flow-icon">
                            <i class="fa-solid fa-database"></i>
                        </div>
                        <div>
                            Data Sources
                        </div>
                    </div>

                    <div class="flow-arrow">
                        ↓
                    </div>

                    <div class="flow-item">
                        <div class="flow-icon">
                            <i class="fa-solid fa-code"></i>
                        </div>
                        <div>
                            SQL & Python
                        </div>
                    </div>

                    <div class="flow-arrow">
                        ↓
                    </div>

                    <div class="flow-item">
                        <div class="flow-icon">
                            <i class="fa-solid fa-chart-line"></i>
                        </div>
                        <div>
                            BI & Dashboards
                        </div>
                    </div>

                    <div class="flow-arrow">
                        ↓
                    </div>

                    <div class="flow-item">
                        <div class="flow-icon">
                            <i class="fa-solid fa-lightbulb"></i>
                        </div>
                        <div>
                            Business Insights
                        </div>
                    </div>

                </div>

            </div>

        </div>

    </div>

</section>


<!-- =========================
     STATS
========================= -->

<div class="stats">

    <div class="container">

        <div class="stats-grid">

            <div class="stat">
                <h3>5+</h3>
                <p>Years Analytics Experience</p>
            </div>

            <div class="stat">
                <h3>100K+</h3>
                <p>Records Analysed</p>
            </div>

            <div class="stat">
                <h3>40+</h3>
                <p>Dashboards & Reports</p>
            </div>

            <div class="stat">
                <h3>SQL</h3>
                <p>Core Analytics Skill</p>
            </div>

        </div>

    </div>

</div>


<!-- =========================
     ABOUT
========================= -->

<section id="about">

    <div class="container">

        <div class="section-label">
            About Me
        </div>

        <h2 class="section-title">
            Data analyst with a business-first mindset.
        </h2>

        <div class="about-grid">

            <div class="about-text">

                <p>
                    I specialise in turning complex datasets into
                    reliable analysis, dashboards and actionable insights.
                </p>

                <p>
                    My experience spans data services, product analytics,
                    market research and business intelligence, giving me
                    both technical and business perspectives.
                </p>

                <p>
                    I enjoy working across the full analytics lifecycle —
                    understanding the question, preparing the data,
                    validating results and communicating the answer clearly.
                </p>

            </div>

            <div class="about-box">

                <h3>What I bring</h3>

                <ul class="about-list">

                    <li>
                        <i class="fa-solid fa-check"></i>
                        Advanced SQL & data analysis
                    </li>

                    <li>
                        <i class="fa-solid fa-check"></i>
                        Python & data manipulation
                    </li>

                    <li>
                        <i class="fa-solid fa-check"></i>
                        Power BI, Tableau & Looker
                    </li>

                    <li>
                        <i class="fa-solid fa-check"></i>
                        Data quality & validation
                    </li>

                    <li>
                        <i class="fa-solid fa-check"></i>
                        Stakeholder & business collaboration
                    </li>

                </ul>

            </div>

        </div>

    </div>

</section>


<!-- =========================
     APPROACH
========================= -->

<section id="approach" class="workflow">

    <div class="container">

        <div class="section-label">
            How I Work
        </div>

        <h2 class="section-title">
            From business question to insight.
        </h2>

        <p class="section-description">
            My approach combines technical analysis with a focus on
            business context and data quality.
        </p>


        <div class="workflow-grid">

            <div class="workflow-card">

                <div class="workflow-number">
                    01
                </div>

                <h3>
                    Understand
                </h3>

                <p>
                    Define the business problem, requirements,
                    KPIs and decisions the analysis needs to support.
                </p>

            </div>


            <div class="workflow-card">

                <div class="workflow-number">
                    02
                </div>

                <h3>
                    Prepare
                </h3>

                <p>
                    Extract, clean, join and validate data from
                    multiple sources.
                </p>

            </div>


            <div class="workflow-card">

                <div class="workflow-number">
                    03
                </div>

                <h3>
                    Analyse
                </h3>

                <p>
                    Use SQL, Python and analytical techniques to
                    identify trends, issues and opportunities.
                </p>

            </div>


            <div class="workflow-card">

                <div class="workflow-number">
                    04
                </div>

                <h3>
                    Communicate
                </h3>

                <p>
                    Turn findings into dashboards, reports and
                    clear recommendations for stakeholders.
                </p>

            </div>

        </div>

    </div>

</section>


<!-- =========================
     PROJECTS
========================= -->

<section id="projects">

    <div class="container">

        <div class="section-label">
            Selected Work
        </div>

        <h2 class="section-title">
            Featured Projects
        </h2>

        <p class="section-description">
            A selection of analytics projects demonstrating SQL,
            Python, BI, data quality and business analysis.
        </p>


        <div class="projects-grid">


            <!-- PROJECT 1 -->

            <div class="project">

                <div class="project-image">
                    <i class="fa-solid fa-chart-column"></i>
                </div>

                <div class="project-content">

                    <span class="project-tag">
                        BUSINESS INTELLIGENCE
                    </span>

                    <h3>
                        Sales & Performance Dashboard
                    </h3>

                    <p>
                        Interactive dashboard designed to analyse
                        business performance, trends, KPIs and
                        operational metrics.
                    </p>

                    <div class="tech">

                        <span>Power BI</span>
                        <span>SQL</span>
                        <span>Excel</span>
                        <span>DAX</span>

                    </div>

                    <div class="project-links">

                        <a href="#">
                            View Project →
                        </a>

                        <a href="#">
                            GitHub →
                        </a>

                    </div>

                </div>

            </div>


            <!-- PROJECT 2 -->

            <div class="project">

                <div class="project-image">
                    <i class="fa-solid fa-database"></i>
                </div>

                <div class="project-content">

                    <span class="project-tag">
                        DATA ANALYTICS
                    </span>

                    <h3>
                        Data Quality & Reconciliation Analysis
                    </h3>

                    <p>
                        SQL-based analysis for identifying data
                        discrepancies, validating records and
                        improving reporting reliability.
                    </p>

                    <div class="tech">

                        <span>SQL</span>
                        <span>Snowflake</span>
                        <span>Oracle</span>
                        <span>Python</span>

                    </div>

                    <div class="project-links">

                        <a href="#">
                            Case Study →
                        </a>

                        <a href="#">
                            GitHub →
                        </a>

                    </div>

                </div>

            </div>


            <!-- PROJECT 3 -->

            <div class="project">

                <div class="project-image">
                    <i class="fa-solid fa-chart-line"></i>
                </div>

                <div class="project-content">

                    <span class="project-tag">
                        PRODUCT ANALYTICS
                    </span>

                    <h3>
                        Product Usage & Customer Analytics
                    </h3>

                    <p>
                        Analysis of product usage patterns,
                        customer behaviour and performance metrics
                        to support product decisions.
                    </p>

                    <div class="tech">

                        <span>Python</span>
                        <span>SQL</span>
                        <span>Tableau</span>
                        <span>Looker</span>

                    </div>

                    <div class="project-links">

                        <a href="#">
                            View Project →
                        </a>

                        <a href="#">
                            GitHub →
                        </a>

                    </div>

                </div>

            </div>


            <!-- PROJECT 4 -->

            <div class="project">

                <div class="project-image">
                    <i class="fa-solid fa-gears"></i>
                </div>

                <div class="project-content">

                    <span class="project-tag">
                        DATA AUTOMATION
                    </span>

                    <h3>
                        Analytics Workflow Automation
                    </h3>

                    <p>
                        Automated repetitive data preparation and
                        validation tasks to reduce manual effort and
                        improve turnaround time.
                    </p>

                    <div class="tech">

                        <span>Python</span>
                        <span>Pandas</span>
                        <span>SQL</span>
                        <span>APIs</span>

                    </div>

                    <div class="project-links">

                        <a href="#">
                            View Project →
                        </a>

                        <a href="#">
                            GitHub →
                        </a>

                    </div>

                </div>

            </div>

        </div>

    </div>

</section>


<!-- =========================
     SKILLS
========================= -->

<section id="skills" class="skills">

    <div class="container">

        <div class="section-label">
            Technical Skills
        </div>

        <h2 class="section-title">
            Tools I work with
        </h2>

        <div class="skills-grid">


            <div class="skill-card">

                <h3>
                    Analytics
                </h3>

                <p>
                    SQL, data analysis, KPI design,
                    data validation, data quality,
                    exploratory analysis and reporting.
                </p>

            </div>


            <div class="skill-card">

                <h3>
                    BI & Visualisation
                </h3>

                <p>
                    Power BI, Tableau, Looker,
                    Excel, dashboard design,
                    KPI reporting and data storytelling.
                </p>

            </div>


            <div class="skill-card">

                <h3>
                    Programming
                </h3>

                <p>
                    Python, Pandas, NumPy,
                    Matplotlib, API integration
                    and automation.
                </p>

            </div>


            <div class="skill-card">

                <h3>
                    Databases
                </h3>

                <p>
                    Snowflake, Redshift, Oracle,
                    PostgreSQL, MySQL and MongoDB.
                </p>

            </div>


            <div class="skill-card">

                <h3>
                    Cloud & Data
                </h3>

                <p>
                    AWS S3, AWS EMR,
                    ETL/ELT concepts,
                    data pipelines and warehousing.
                </p>

            </div>


            <div class="skill-card">

                <h3>
                    Collaboration
                </h3>

                <p>
                    Agile, Scrum, Jira, Confluence,
                    Git, UAT, stakeholder communication
                    and requirements analysis.
                </p>

            </div>

        </div>

    </div>

</section>


<!-- =========================
     CONTACT
========================= -->

<section id="contact" class="contact">

    <div class="container">

        <div class="section-label">
            Let's Connect
        </div>

        <h2>
            Interested in working together?
        </h2>

        <p>
            I'm open to Data Analyst, BI, Product Analytics
            and Analytics-focused opportunities.
        </p>

        <div class="buttons"
             style="justify-content:center;">

            <a href="mailto:your-email@example.com"
               class="btn btn-primary">

                Get In Touch

            </a>

        </div>


        <div class="social-links"
             style="margin-top:30px;">

            <a href="https://github.com/krishnapriyadoraiswamy2210"
               target="_blank">

                <i class="fa-brands fa-github"></i>

            </a>

            <a href="#">

                <i class="fa-brands fa-linkedin-in"></i>

            </a>

        </div>

    </div>

</section>


<!-- =========================
     FOOTER
========================= -->

<footer>

    © 2026 Krishnapriya Doraiswamy · Built with HTML, CSS & GitHub Pages

</footer>


</body>
</html>
