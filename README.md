<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Krishnapriya Doraiswamy | Data Analyst</title>

    <meta name="description"
          content="Krishnapriya Doraiswamy - Data Analyst specialising in SQL, Python, Power BI, data analytics and business intelligence.">

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
            font-family: Arial, Helvetica, sans-serif;
            background: #f7f8fc;
            color: #172033;
            line-height: 1.6;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* NAVIGATION */

        nav {
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
            background: rgba(255, 255, 255, 0.95);
            border-bottom: 1px solid #e7e9ef;
        }

        .nav-container {
            max-width: 1100px;
            margin: auto;
            padding: 18px 25px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 20px;
            font-weight: 700;
            color: #111827;
        }

        .nav-links {
            display: flex;
            gap: 28px;
            list-style: none;
        }

        .nav-links a {
            font-size: 14px;
            color: #4b5563;
            transition: 0.2s;
        }

        .nav-links a:hover {
            color: #4f46e5;
        }

        /* HERO */

        .hero {
            min-height: 100vh;
            display: flex;
            align-items: center;
            padding: 120px 25px 80px;
        }

        .hero-container {
            max-width: 1100px;
            width: 100%;
            margin: auto;
            display: grid;
            grid-template-columns: 1.4fr 0.6fr;
            gap: 60px;
            align-items: center;
        }

        .eyebrow {
            color: #4f46e5;
            font-weight: 700;
            font-size: 15px;
            margin-bottom: 15px;
            letter-spacing: 0.5px;
        }

        h1 {
            font-size: clamp(45px, 7vw, 76px);
            line-height: 1.05;
            letter-spacing: -3px;
            margin-bottom: 25px;
            color: #111827;
        }

        .hero h1 span {
            color: #4f46e5;
        }

        .hero-description {
            font-size: 19px;
            max-width: 650px;
            color: #5b6474;
            margin-bottom: 35px;
        }

        .buttons {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
        }

        .button {
            padding: 13px 23px;
            border-radius: 8px;
            font-weight: 600;
            font-size: 14px;
            border: 1px solid #d9dce5;
            transition: 0.2s;
        }

        .button-primary {
            background: #4f46e5;
            color: white;
            border-color: #4f46e5;
        }

        .button-primary:hover {
            background: #4338ca;
        }

        .button-secondary {
            background: white;
        }

        .button-secondary:hover {
            border-color: #4f46e5;
            color: #4f46e5;
        }

        /* HERO CARD */

        .profile-card {
            background: white;
            border: 1px solid #e5e7eb;
            border-radius: 20px;
            padding: 35px;
            box-shadow: 0 15px 40px rgba(20, 30, 60, 0.08);
        }

        .profile-icon {
            width: 90px;
            height: 90px;
            border-radius: 50%;
            background: #eef2ff;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 35px;
            font-weight: 700;
            color: #4f46e5;
            margin-bottom: 25px;
        }

        .profile-card h3 {
            margin-bottom: 8px;
        }

        .profile-card p {
            color: #697386;
            font-size: 14px;
        }

        .stat {
            margin-top: 25px;
            padding-top: 20px;
            border-top: 1px solid #eee;
        }

        .stat strong {
            display: block;
            font-size: 25px;
            color: #111827;
        }

        .stat span {
            font-size: 13px;
            color: #697386;
        }

        /* SECTIONS */

        section {
            padding: 100px 25px;
        }

        .section-container {
            max-width: 1100px;
            margin: auto;
        }

        .section-label {
            color: #4f46e5;
            font-weight: 700;
            font-size: 13px;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 10px;
        }

        .section-title {
            font-size: 38px;
            margin-bottom: 45px;
            letter-spacing: -1px;
        }

        /* ABOUT */

        .about {
            background: white;
        }

        .about-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
        }

        .about-text {
            color: #596273;
            font-size: 16px;
        }

        .about-text p {
            margin-bottom: 18px;
        }

        .highlights {
            display: grid;
            gap: 15px;
        }

        .highlight {
            background: #f7f8fc;
            border: 1px solid #e8eaf0;
            border-radius: 12px;
            padding: 20px;
        }

        .highlight strong {
            display: block;
            margin-bottom: 5px;
            color: #111827;
        }

        .highlight span {
            color: #697386;
            font-size: 14px;
        }

        /* SKILLS */

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }

        .skill-card {
            background: white;
            border: 1px solid #e5e7eb;
            border-radius: 14px;
            padding: 25px;
        }

        .skill-card h3 {
            margin-bottom: 15px;
            font-size: 18px;
        }

        .skill-card p {
            color: #697386;
            font-size: 14px;
        }

        /* EXPERIENCE */

        .experience {
            background: white;
        }

        .timeline {
            border-left: 2px solid #e4e6ed;
            padding-left: 30px;
        }

        .job {
            position: relative;
            margin-bottom: 45px;
        }

        .job::before {
            content: "";
            position: absolute;
            left: -38px;
            top: 5px;
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: #4f46e5;
        }

        .job-date {
            color: #4f46e5;
            font-size: 13px;
            font-weight: 700;
            margin-bottom: 6px;
        }

        .job h3 {
            font-size: 21px;
            margin-bottom: 3px;
        }

        .job-company {
            color: #697386;
            margin-bottom: 12px;
        }

        .job p {
            color: #596273;
            font-size: 15px;
            max-width: 800px;
        }

        /* PROJECTS */

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 25px;
        }

        .project {
            background: white;
            border: 1px solid #e5e7eb;
            border-radius: 15px;
            padding: 30px;
            transition: 0.2s;
        }

        .project:hover {
            transform: translateY(-4px);
            box-shadow: 0 15px 35px rgba(20, 30, 60, 0.08);
        }

        .project-number {
            color: #4f46e5;
            font-weight: 700;
            margin-bottom: 15px;
        }

        .project h3 {
            margin-bottom: 10px;
            font-size: 21px;
        }

        .project p {
            color: #697386;
            font-size: 14px;
            margin-bottom: 18px;
        }

        .tags {
            display: flex;
            gap: 8px;
            flex-wrap: wrap;
        }

        .tag {
            background: #eef2ff;
            color: #4338ca;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 600;
        }

        /* EDUCATION */

        .education {
            background: white;
        }

        .education-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 25px;
        }

        .education-card {
            border: 1px solid #e5e7eb;
            border-radius: 14px;
            padding: 25px;
        }

        .education-card h3 {
            margin-bottom: 8px;
        }

        .education-card p {
            color: #697386;
            font-size: 14px;
        }

        /* CONTACT */

        .contact {
            text-align: center;
        }

        .contact-text {
            max-width: 600px;
            margin: 0 auto 30px;
            color: #697386;
        }

        /* FOOTER */

        footer {
            background: #111827;
            color: #9ca3af;
            text-align: center;
            padding: 30px 20px;
            font-size: 13px;
        }

        /* MOBILE */

        @media (max-width: 800px) {

            .nav-links {
                display: none;
            }

            .hero-container,
            .about-grid,
            .education-grid {
                grid-template-columns: 1fr;
            }

            .skills-grid {
                grid-template-columns: 1fr;
            }

            .projects-grid {
                grid-template-columns: 1fr;
            }

            h1 {
                letter-spacing: -2px;
            }

            .profile-card {
                max-width: 400px;
            }
        }
    </style>
</head>

<body>

<!-- NAVIGATION -->

<nav>
    <div class="nav-container">
        <div class="logo">KD.</div>

        <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </div>
</nav>


<!-- HERO -->

<header class="hero">

    <div class="hero-container">

        <div>

            <div class="eyebrow">
                DATA ANALYST · BI · ANALYTICS
            </div>

            <h1>
                Hi, I'm<br>
                <span>Krishnapriya.</span>
            </h1>

            <p class="hero-description">
                I turn complex data into clear insights, reliable reporting
                and business-ready solutions using SQL, Python and modern BI
                technologies.
            </p>

            <div class="buttons">

                <a href="#projects" class="button button-primary">
                    View My Work
                </a>

                <a href="#contact" class="button button-secondary">
                    Get In Touch
                </a>

            </div>

        </div>


        <div class="profile-card">

            <div class="profile-icon">
                KD
            </div>

            <h3>
                Data Analyst
            </h3>

            <p>
                Business Intelligence · Data Products · Analytics
            </p>

            <div class="stat">
                <strong>5+</strong>
                <span>Years of analytics experience</span>
            </div>

            <div class="stat">
                <strong>SQL</strong>
                <span>Data transformation & analysis</span>
            </div>

        </div>

    </div>

</header>


<!-- ABOUT -->

<section id="about" class="about">

    <div class="section-container">

        <div class="section-label">
            About Me
        </div>

        <h2 class="section-title">
            Turning data into decisions.
        </h2>

        <div class="about-grid">

            <div class="about-text">

                <p>
                    I'm a data and analytics professional with 5+ years of
                    experience working across data analysis, business
                    intelligence, market research and data services.
                </p>

                <p>
                    My work sits between business problems and technical
                    solutions — from extracting and transforming data with
                    SQL and Python to building dashboards and validating
                    data quality.
                </p>

                <p>
                    I enjoy understanding how data moves through a business
                    and turning that data into something useful, reliable
                    and easy to understand.
                </p>

            </div>

            <div class="highlights">

                <div class="highlight">
                    <strong>Data Analytics</strong>
                    <span>
                        SQL, Python, data cleaning, transformation and analysis
                    </span>
                </div>

                <div class="highlight">
                    <strong>Business Intelligence</strong>
                    <span>
                        Power BI, Tableau, Looker and data visualisation
                    </span>
                </div>

                <div class="highlight">
                    <strong>Data Quality</strong>
                    <span>
                        Validation, reconciliation, ETL and source-to-target mapping
                    </span>
                </div>

                <div class="highlight">
                    <strong>Stakeholder Collaboration</strong>
                    <span>
                        Translating business requirements into analytical solutions
                    </span>
                </div>

            </div>

        </div>

    </div>

</section>


<!-- SKILLS -->

<section id="skills">

    <div class="section-container">

        <div class="section-label">
            Technical Skills
        </div>

        <h2 class="section-title">
            Tools I work with.
        </h2>

        <div class="skills-grid">

            <div class="skill-card">
                <h3>Data & SQL</h3>
                <p>
                    SQL · T-SQL · CTEs · Window Functions · Query Optimisation
                    · ETL · Data Validation · Data Quality
                </p>
            </div>

            <div class="skill-card">
                <h3>Programming</h3>
                <p>
                    Python · Pandas · NumPy · Matplotlib · API Integration
                </p>
            </div>

            <div class="skill-card">
                <h3>Business Intelligence</h3>
                <p>
                    Power BI · Tableau · Looker · Excel · Data Visualisation
                </p>
            </div>

            <div class="skill-card">
                <h3>Databases</h3>
                <p>
                    Snowflake · Redshift · Oracle · PostgreSQL · MySQL · MongoDB
                </p>
            </div>

            <div class="skill-card">
                <h3>Cloud & Data</h3>
                <p>
                    AWS · S3 · EMR · Data Warehousing · Data Pipelines
                </p>
            </div>

            <div class="skill-card">
                <h3>Ways of Working</h3>
                <p>
                    Agile · Scrum · Kanban · Jira · Confluence · Git · UAT
                </p>
            </div>

        </div>

    </div>

</section>


<!-- EXPERIENCE -->

<section id="experience" class="experience">

    <div class="section-container">

        <div class="section-label">
            Experience
        </div>

        <h2 class="section-title">
            Where I've worked.
        </h2>

        <div class="timeline">

            <div class="job">

                <div class="job-date">
                    MAR 2025 — MAR 2026
                </div>

                <h3>
                    Data Services Analyst
                </h3>

                <div class="job-company">
                    Lloyd's List Intelligence
                </div>

                <p>
                    Worked with large maritime datasets, supporting data
                    transformation, validation, reconciliation and source-to-
                    target mapping across Oracle, Snowflake and Redshift.
                    Used SQL, Python and APIs to investigate data issues and
                    improve operational workflows.
                </p>

            </div>


            <div class="job">

                <div class="job-date">
                    JUN 2023 — OCT 2024
                </div>

                <h3>
                    Product Analyst
                </h3>

                <div class="job-company">
                    Responsive
                </div>

                <p>
                    Analysed product and customer data using Python, SQL and
                    BI tools. Built dashboards, supported data warehouse
                    initiatives, worked with APIs and collaborated with
                    product and engineering teams through UAT and Agile
                    delivery.
                </p>

            </div>


            <div class="job">

                <div class="job-date">
                    EARLIER EXPERIENCE
                </div>

                <h3>
                    Market Research & Analytics
                </h3>

                <div class="job-company">
                    Zinnov
                </div>

                <p>
                    Conducted technology and market research, analysed
                    datasets and translated research findings into structured
                    business insights and client-facing deliverables.
                </p>

            </div>

        </div>

    </div>

</section>


<!-- PROJECTS -->

<section id="projects">

    <div class="section-container">

        <div class="section-label">
            Featured Work
        </div>

        <h2 class="section-title">
            Projects & case studies.
        </h2>

        <div class="projects-grid">

            <div class="project">

                <div class="project-number">
                    01
                </div>

                <h3>
                    Data Quality & Reconciliation
                </h3>

                <p>
                    Designed SQL-based validation and reconciliation logic
                    to investigate discrepancies across large operational
                    datasets and improve data reliability.
                </p>

                <div class="tags">
                    <span class="tag">SQL</span>
                    <span class="tag">Snowflake</span>
                    <span class="tag">Data Quality</span>
                    <span class="tag">ETL</span>
                </div>

            </div>


            <div class="project">

                <div class="project-number">
                    02
                </div>

                <h3>
                    Business Intelligence Dashboard
                </h3>

                <p>
                    Created interactive BI dashboards to transform raw
                    business data into accessible performance insights
                    for stakeholders.
                </p>

                <div class="tags">
                    <span class="tag">Power BI</span>
                    <span class="tag">SQL</span>
                    <span class="tag">Data Visualisation</span>
                </div>

            </div>


            <div class="project">

                <div class="project-number">
                    03
                </div>

                <h3>
                    Customer & Product Analytics
                </h3>

                <p>
                    Analysed customer and product behaviour using Python,
                    segmentation and BI reporting to support product
                    decision-making.
                </p>

                <div class="tags">
                    <span class="tag">Python</span>
                    <span class="tag">Pandas</span>
                    <span class="tag">Tableau</span>
                    <span class="tag">Looker</span>
                </div>

            </div>


            <div class="project">

                <div class="project-number">
                    04
                </div>

                <h3>
                    SQL Analytics Case Study
                </h3>

                <p>
                    A collection of practical SQL analysis covering joins,
                    aggregations, CTEs, window functions, ranking and
                    business-focused problem solving.
                </p>

                <div class="tags">
                    <span class="tag">SQL</span>
                    <span class="tag">CTEs</span>
                    <span class="tag">Window Functions</span>
                </div>

            </div>

        </div>

    </div>

</section>


<!-- EDUCATION -->

<section class="education">

    <div class="section-container">

        <div class="section-label">
            Education
        </div>

        <h2 class="section-title">
            Academic background.
        </h2>

        <div class="education-grid">

            <div class="education-card">

                <h3>
                    MSc Computer Science
                </h3>

                <p>
                    Bharathiar University
                </p>

                <p>
                    2017 — 2019
                </p>

            </div>


            <div class="education-card">

                <h3>
                    BSc Computer Science
                </h3>

                <p>
                    Bharathiar University
                </p>

                <p>
                    2014 — 2017
                </p>

            </div>

        </div>

    </div>

</section>


<!-- CONTACT -->

<section id="contact" class="contact">

    <div class="section-container">

        <div class="section-label">
            Contact
        </div>

        <h2 class="section-title">
            Let's connect.
        </h2>

        <p class="contact-text">
            I'm interested in data analytics, business intelligence,
            analytics engineering and data-focused product roles.
        </p>

        <div class="buttons" style="justify-content:center;">

            <a href="mailto:YOUR_EMAIL@example.com"
               class="button button-primary">
                Email Me
            </a>

            <a href="https://www.linkedin.com/"
               class="button button-secondary">
                LinkedIn
            </a>

        </div>

    </div>

</section>


<!-- FOOTER -->

<footer>

    © 2026 Krishnapriya Doraiswamy · Data Analyst & BI Professional

</footer>

</body>
</html>
