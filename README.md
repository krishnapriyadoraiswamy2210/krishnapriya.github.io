<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Krishnapriya Doraiswamy | Data Analyst</title>

    <meta name="description"
          content="Krishnapriya Doraiswamy — Data Analyst specialising in SQL, Power BI, Python, data quality and analytics.">

    <style>

        /* =========================
           RESET
        ========================= */

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
            background: #f7f7f4;
            color: #111;
            line-height: 1.5;
        }

        a {
            color: inherit;
            text-decoration: none;
        }

        /* =========================
           GLOBAL
        ========================= */

        .page {
            width: 100%;
        }

        .container {
            width: min(1400px, 92%);
            margin: auto;
        }

        section {
            width: 100%;
            padding: 110px 0;
            border-top: 1px solid #d8d8d3;
        }

        .section-number {
            font-size: 13px;
            font-weight: 700;
            letter-spacing: 0.12em;
            text-transform: uppercase;
            margin-bottom: 25px;
        }

        h1, h2, h3, h4 {
            font-weight: 500;
            letter-spacing: -0.04em;
        }

        h2 {
            font-size: clamp(42px, 6vw, 85px);
            line-height: 0.95;
            margin-bottom: 45px;
        }

        .muted {
            color: #777;
        }

        /* =========================
           NAVIGATION
        ========================= */

        header {
            width: 100%;
            padding: 25px 0;
            border-bottom: 1px solid #d8d8d3;
        }

        nav {
            width: min(1400px, 92%);
            margin: auto;

            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-weight: 700;
            font-size: 15px;
        }

        .nav-links {
            display: flex;
            gap: 30px;
            font-size: 14px;
        }

        .nav-links a {
            transition: opacity 0.2s ease;
        }

        .nav-links a:hover {
            opacity: 0.45;
        }

        /* =========================
           HERO
        ========================= */

        .hero {
            min-height: 90vh;
            display: flex;
            align-items: center;
            padding: 80px 0 120px;
        }

        .hero-grid {
            display: grid;
            grid-template-columns: 1.5fr 1fr;
            gap: 80px;
            align-items: end;
        }

        .hero h1 {
            font-size: clamp(70px, 13vw, 180px);
            line-height: 0.8;
            letter-spacing: -0.075em;
        }

        .hero-description {
            max-width: 480px;
            font-size: 21px;
            line-height: 1.4;
        }

        .hero-stats {
            margin-top: 55px;

            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        .stat {
            border-top: 1px solid #aaa;
            padding-top: 15px;
        }

        .stat-number {
            font-size: 30px;
            font-weight: 500;
        }

        .stat-label {
            font-size: 13px;
            color: #777;
            margin-top: 5px;
        }

        .hero-buttons {
            margin-top: 45px;
            display: flex;
            gap: 12px;
            flex-wrap: wrap;
        }

        .button {
            display: inline-block;
            border: 1px solid #111;
            padding: 13px 22px;
            font-size: 14px;
            transition: all 0.2s ease;
        }

        .button:hover {
            background: #111;
            color: #fff;
        }

        /* =========================
           INTRO / STATEMENT
        ========================= */

        .statement {
            max-width: 1050px;
            font-size: clamp(30px, 4vw, 58px);
            line-height: 1.05;
            letter-spacing: -0.045em;
        }

        /* =========================
           PROJECTS
        ========================= */

        .projects-intro {
            max-width: 650px;
            font-size: 19px;
            color: #666;
            margin-bottom: 60px;
        }

        .project-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 2px;
            background: #d8d8d3;
            border: 1px solid #d8d8d3;
        }

        .project {
            background: #f7f7f4;
            padding: 40px;

            min-height: 390px;

            display: flex;
            flex-direction: column;
            justify-content: space-between;

            transition: background 0.25s ease;
        }

        .project:hover {
            background: #eeeeea;
        }

        .project-top {
            display: flex;
            justify-content: space-between;
            font-size: 12px;
            text-transform: uppercase;
            letter-spacing: 0.08em;
        }

        .project h3 {
            font-size: 38px;
            line-height: 1;
            margin: 45px 0 20px;
        }

        .project p {
            max-width: 600px;
            color: #666;
            font-size: 16px;
        }

        .tags {
            margin-top: 25px;

            display: flex;
            gap: 8px;
            flex-wrap: wrap;
        }

        .tag {
            border: 1px solid #c9c9c4;
            padding: 5px 10px;
            font-size: 11px;
            text-transform: uppercase;
        }

        /* =========================
           EXPERIENCE
        ========================= */

        .experience {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 80px;
        }

        .experience-list {
            border-top: 1px solid #aaa;
        }

        .experience-item {
            padding: 30px 0;
            border-bottom: 1px solid #aaa;

            display: grid;
            grid-template-columns: 180px 1fr;
            gap: 30px;
        }

        .experience-date {
            color: #777;
            font-size: 14px;
        }

        .experience-item h3 {
            font-size: 28px;
            margin-bottom: 8px;
        }

        .experience-company {
            font-size: 15px;
            margin-bottom: 15px;
        }

        .experience-item p {
            color: #666;
            max-width: 700px;
        }

        /* =========================
           SKILLS
        ========================= */

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 2px;
            background: #d8d8d3;
            border: 1px solid #d8d8d3;
        }

        .skill-box {
            background: #f7f7f4;
            padding: 35px;
            min-height: 250px;
        }

        .skill-box h3 {
            font-size: 27px;
            margin-bottom: 30px;
        }

        .skill-list {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }

        .skill {
            padding: 7px 11px;
            border: 1px solid #ccc;
            font-size: 13px;
        }

        /* =========================
           ABOUT
        ========================= */

        .about-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 100px;
        }

        .about-text {
            font-size: 24px;
            line-height: 1.3;
        }

        .about-details {
            font-size: 16px;
            color: #666;
        }

        .about-details p {
            margin-bottom: 25px;
        }

        /* =========================
           CONTACT
        ========================= */

        .contact {
            min-height: 70vh;
            display: flex;
            align-items: center;
        }

        .contact h2 {
            max-width: 1000px;
            margin-bottom: 40px;
        }

        .email {
            font-size: clamp(25px, 4vw, 55px);
            border-bottom: 2px solid #111;
            display: inline-block;
            letter-spacing: -0.04em;
        }

        /* =========================
           FOOTER
        ========================= */

        footer {
            border-top: 1px solid #d8d8d3;
            padding: 30px 0;
        }

        .footer-inner {
            width: min(1400px, 92%);
            margin: auto;

            display: flex;
            justify-content: space-between;
            font-size: 13px;
            color: #777;
        }

        /* =========================
           MOBILE
        ========================= */

        @media (max-width: 900px) {

            .hero-grid,
            .experience,
            .about-grid {
                grid-template-columns: 1fr;
                gap: 50px;
            }

            .hero {
                min-height: auto;
                padding: 80px 0;
            }

            .hero h1 {
                font-size: 19vw;
            }

            .project-grid,
            .skills-grid {
                grid-template-columns: 1fr;
            }

            .experience-item {
                grid-template-columns: 1fr;
                gap: 10px;
            }

            .hero-stats {
                grid-template-columns: 1fr 1fr;
            }

            .nav-links {
                gap: 15px;
            }
        }

        @media (max-width: 600px) {

            section {
                padding: 75px 0;
            }

            .nav-links {
                display: none;
            }

            .hero-description {
                font-size: 18px;
            }

            .project {
                padding: 28px;
                min-height: 340px;
            }

            .project h3 {
                font-size: 31px;
            }

            .hero-stats {
                grid-template-columns: 1fr;
            }

            .footer-inner {
                flex-direction: column;
                gap: 10px;
            }
        }

    </style>
</head>

<body>

<div class="page">

    <!-- =========================
         NAVIGATION
    ========================== -->

    <header>

        <nav>

            <a href="#" class="logo">
                KRISHNAPRIYA DORAISWAMY
            </a>

            <div class="nav-links">
                <a href="#work">Work</a>
                <a href="#experience">Experience</a>
                <a href="#skills">Skills</a>
                <a href="#about">About</a>
                <a href="#contact">Contact</a>
            </div>

        </nav>

    </header>


    <!-- =========================
         HERO
    ========================== -->

    <main>

        <section class="hero">

            <div class="container">

                <div class="hero-grid">

                    <div>

                        <h1>
                            Krishnapriya
                        </h1>

                        <div class="hero-stats">

                            <div class="stat">
                                <div class="stat-number">5+</div>
                                <div class="stat-label">
                                    Years in analytics
                                </div>
                            </div>

                            <div class="stat">
                                <div class="stat-number">SQL</div>
                                <div class="stat-label">
                                    Data & analytics
                                </div>
                            </div>

                            <div class="stat">
                                <div class="stat-number">BI</div>
                                <div class="stat-label">
                                    Reporting & insights
                                </div>
                            </div>

                        </div>

                    </div>


                    <div>

                        <p class="hero-description">

                            I build reliable data solutions that turn
                            complex datasets into clear insights,
                            dashboards and decisions.

                        </p>

                        <div class="hero-buttons">

                            <a href="#work" class="button">
                                View my work
                            </a>

                            <a href="CV.pdf"
                               class="button"
                               target="_blank">
                                Résumé
                            </a>

                        </div>

                    </div>

                </div>

            </div>

        </section>


        <!-- =========================
             STATEMENT
        ========================== -->

        <section>

            <div class="container">

                <div class="section-number">
                    01 — What I do
                </div>

                <p class="statement">

                    I work across data analysis, business
                    intelligence and data services — connecting
                    raw data to useful business outcomes.

                </p>

            </div>

        </section>


        <!-- =========================
             PROJECTS
        ========================== -->

        <section id="work">

            <div class="container">

                <div class="section-number">
                    02 — Selected work
                </div>

                <h2>
                    Data projects
                </h2>

                <p class="projects-intro">

                    A selection of work demonstrating SQL,
                    Python, BI, data quality, transformation,
                    reporting and analytics.

                </p>


                <div class="project-grid">


                    <!-- PROJECT 1 -->

                    <article class="project">

                        <div>

                            <div class="project-top">
                                <span>01</span>
                                <span>Data Services</span>
                            </div>

                            <h3>
                                Maritime Data Quality
                            </h3>

                            <p>

                                Analysed large maritime datasets
                                containing vessel, AIS, ownership
                                and movement information. Used SQL
                                and Python to investigate discrepancies,
                                validate transformations and improve
                                data quality.

                            </p>

                        </div>

                        <div class="tags">

                            <span class="tag">SQL</span>
                            <span class="tag">Python</span>
                            <span class="tag">Snowflake</span>
                            <span class="tag">Oracle</span>

                        </div>

                    </article>


                    <!-- PROJECT 2 -->

                    <article class="project">

                        <div>

                            <div class="project-top">
                                <span>02</span>
                                <span>Business Intelligence</span>
                            </div>

                            <h3>
                                BI Reporting
                            </h3>

                            <p>

                                Developed dashboards and reporting
                                solutions to transform business data
                                into actionable insights for
                                stakeholders.

                            </p>

                        </div>

                        <div class="tags">

                            <span class="tag">Power BI</span>
                            <span class="tag">Tableau</span>
                            <span class="tag">SQL</span>
                            <span class="tag">Excel</span>

                        </div>

                    </article>


                    <!-- PROJECT 3 -->

                    <article class="project">

                        <div>

                            <div class="project-top">
                                <span>03</span>
                                <span>Product Analytics</span>
                            </div>

                            <h3>
                                Product Analytics
                            </h3>

                            <p>

                                Analysed product and customer data
                                using Python, SQL and BI tools to
                                identify patterns, improve reporting
                                and support product decisions.

                            </p>

                        </div>

                        <div class="tags">

                            <span class="tag">Python</span>
                            <span class="tag">SQL</span>
                            <span class="tag">Looker</span>
                            <span class="tag">Tableau</span>

                        </div>

                    </article>


                    <!-- PROJECT 4 -->

                    <article class="project">

                        <div>

                            <div class="project-top">
                                <span>04</span>
                                <span>Data Automation</span>
                            </div>

                            <h3>
                                Data Validation & Automation
                            </h3>

                            <p>

                                Automated repetitive data validation
                                and reconciliation processes,
                                reducing manual effort and improving
                                turnaround times.

                            </p>

                        </div>

                        <div class="tags">

                            <span class="tag">Python</span>
                            <span class="tag">SQL</span>
                            <span class="tag">ETL</span>
                            <span class="tag">APIs</span>

                        </div>

                    </article>

                </div>

            </div>

        </section>


        <!-- =========================
             EXPERIENCE
        ========================== -->

        <section id="experience">

            <div class="container">

                <div class="section-number">
                    03 — Experience
                </div>

                <div class="experience">

                    <div>

                        <h2>
                            From data<br>
                            to decisions
                        </h2>

                    </div>


                    <div class="experience-list">


                        <div class="experience-item">

                            <div class="experience-date">
                                2025 — 2026
                            </div>

                            <div>

                                <h3>
                                    Data Services Analyst
                                </h3>

                                <div class="experience-company">
                                    Lloyd's List Intelligence
                                </div>

                                <p>

                                    Worked with large-scale maritime
                                    datasets using SQL, Python,
                                    Snowflake, Redshift and Oracle.
                                    Focused on data validation,
                                    reconciliation, transformation
                                    and quality analysis.

                                </p>

                            </div>

                        </div>


                        <div class="experience-item">

                            <div class="experience-date">
                                2023 — 2024
                            </div>

                            <div>

                                <h3>
                                    Product Analyst
                                </h3>

                                <div class="experience-company">
                                    Responsive
                                </div>

                                <p>

                                    Analysed product and customer
                                    behaviour using SQL and Python,
                                    created BI dashboards and worked
                                    with cross-functional teams
                                    through UAT and Agile delivery.

                                </p>

                            </div>

                        </div>


                        <div class="experience-item">

                            <div class="experience-date">
                                Earlier
                            </div>

                            <div>

                                <h3>
                                    Market Research & Analytics
                                </h3>

                                <div class="experience-company">
                                    Zinnov
                                </div>

                                <p>

                                    Delivered technology and market
                                    intelligence analysis using
                                    structured research, data analysis
                                    and visualisation.

                                </p>

                            </div>

                        </div>

                    </div>

                </div>

            </div>

        </section>


        <!-- =========================
             SKILLS
        ========================== -->

        <section id="skills">

            <div class="container">

                <div class="section-number">
                    04 — Skills & tooling
                </div>

                <h2>
                    The stack<br>
                    I work with
                </h2>


                <div class="skills-grid">


                    <div class="skill-box">

                        <h3>
                            Data & SQL
                        </h3>

                        <div class="skill-list">

                            <span class="skill">SQL</span>
                            <span class="skill">T-SQL</span>
                            <span class="skill">CTEs</span>
                            <span class="skill">Window Functions</span>
                            <span class="skill">ETL</span>
                            <span class="skill">Data Quality</span>
                            <span class="skill">Data Validation</span>

                        </div>

                    </div>


                    <div class="skill-box">

                        <h3>
                            BI & Analytics
                        </h3>

                        <div class="skill-list">

                            <span class="skill">Power BI</span>
                            <span class="skill">Tableau</span>
                            <span class="skill">Looker</span>
                            <span class="skill">Excel</span>
                            <span class="skill">Dashboards</span>
                            <span class="skill">Reporting</span>

                        </div>

                    </div>


                    <div class="skill-box">

                        <h3>
                            Python & Data
                        </h3>

                        <div class="skill-list">

                            <span class="skill">Python</span>
                            <span class="skill">Pandas</span>
                            <span class="skill">NumPy</span>
                            <span class="skill">Matplotlib</span>
                            <span class="skill">APIs</span>
                            <span class="skill">Automation</span>

                        </div>

                    </div>


                    <div class="skill-box">

                        <h3>
                            Data Platforms
                        </h3>

                        <div class="skill-list">

                            <span class="skill">Snowflake</span>
                            <span class="skill">Redshift</span>
                            <span class="skill">Oracle</span>
                            <span class="skill">PostgreSQL</span>
                            <span class="skill">MySQL</span>
                            <span class="skill">MongoDB</span>

                        </div>

                    </div>


                    <div class="skill-box">

                        <h3>
                            Cloud & Engineering
                        </h3>

                        <div class="skill-list">

                            <span class="skill">AWS</span>
                            <span class="skill">S3</span>
                            <span class="skill">EMR</span>
                            <span class="skill">Git</span>
                            <span class="skill">Jira</span>
                            <span class="skill">Confluence</span>

                        </div>

                    </div>


                    <div class="skill-box">

                        <h3>
                            Delivery
                        </h3>

                        <div class="skill-list">

                            <span class="skill">Agile</span>
                            <span class="skill">UAT</span>
                            <span class="skill">Stakeholder Management</span>
                            <span class="skill">Requirements</span>
                            <span class="skill">Data Mapping</span>

                        </div>

                    </div>

                </div>

            </div>

        </section>


        <!-- =========================
             ABOUT
        ========================== -->

        <section id="about">

            <div class="container">

                <div class="section-number">
                    05 — About me
                </div>

                <div class="about-grid">

                    <div>

                        <p class="about-text">

                            I'm a data analyst with experience
                            across business intelligence, product
                            analytics and data services.

                        </p>

                    </div>

                    <div class="about-details">

                        <p>

                            My work sits between business questions
                            and technical data. I enjoy understanding
                            where data comes from, validating it,
                            transforming it and presenting it in a
                            way that people can actually use.

                        </p>

                        <p>

                            I'm particularly interested in analytics,
                            BI, modern data platforms and the growing
                            role of AI in data workflows.

                        </p>

                        <p>

                            Based in the UK and open to opportunities
                            across data analytics, BI and analytics
                            engineering.

                        </p>

                    </div>

                </div>

            </div>

        </section>


        <!-- =========================
             CONTACT
        ========================== -->

        <section id="contact" class="contact">

            <div class="container">

                <div class="section-number">
                    06 — Get in touch
                </div>

                <h2>
                    Let's talk about<br>
                    data.
                </h2>

                <a
                    href="mailto:your.email@example.com"
                    class="email">

                    your.email@example.com

                </a>

            </div>

        </section>

    </main>


    <!-- =========================
         FOOTER
    ========================== -->

    <footer>

        <div class="footer-inner">

            <span>
                © 2026 Krishnapriya Doraiswamy
            </span>

            <span>
                Hand-built with HTML & CSS · GitHub Pages
            </span>

        </div>

    </footer>

</div>

</body>
</html>
