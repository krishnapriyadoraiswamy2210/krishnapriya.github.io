<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Krishnapriya Doraiswamy | Data Analyst</title>

    <meta
        name="description"
        content="Krishnapriya Doraiswamy — Data Analyst specialising in SQL, Python, Business Intelligence and data analytics."
    >

    <style>

        /* =====================================================
           RESET
        ===================================================== */

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family:
                Inter,
                -apple-system,
                BlinkMacSystemFont,
                "Segoe UI",
                Arial,
                sans-serif;

            background: #f5f4ef;
            color: #171717;

            min-height: 100vh;
        }

        a {
            color: inherit;
            text-decoration: none;
        }


        /* =====================================================
           PAGE
        ===================================================== */

        .page {
            min-height: 100vh;
            position: relative;
            overflow: hidden;
        }


        /* =====================================================
           BACKGROUND GRID
        ===================================================== */

        .page::before {
            content: "";

            position: absolute;
            inset: 0;

            background-image:
                linear-gradient(
                    to right,
                    rgba(0,0,0,0.035) 1px,
                    transparent 1px
                ),
                linear-gradient(
                    to bottom,
                    rgba(0,0,0,0.035) 1px,
                    transparent 1px
                );

            background-size: 80px 80px;

            pointer-events: none;
        }


        /* =====================================================
           HEADER
        ===================================================== */

        header {
            position: relative;
            z-index: 10;

            width: 100%;

            padding: 28px 5%;

            border-bottom: 1px solid rgba(0,0,0,0.12);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 13px;
            font-weight: 700;

            letter-spacing: 0.12em;
        }

        .nav-right {
            display: flex;
            align-items: center;
            gap: 30px;

            font-size: 12px;
            letter-spacing: 0.1em;
            text-transform: uppercase;

            color: #777;
        }

        .status {
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .status-dot {
            width: 7px;
            height: 7px;

            border-radius: 50%;

            background: #667f5d;
        }


        /* =====================================================
           HERO
        ===================================================== */

        .hero {
            position: relative;
            z-index: 2;

            width: 90%;
            max-width: 1500px;

            min-height: calc(100vh - 78px);

            margin: auto;

            display: flex;
            align-items: center;

            padding: 80px 0 120px;
        }

        .hero-content {
            width: 100%;
        }


        /* =====================================================
           SMALL INTRO
        ===================================================== */

        .eyebrow {
            display: flex;
            align-items: center;
            gap: 15px;

            margin-bottom: 35px;

            font-size: 12px;
            font-weight: 600;

            text-transform: uppercase;
            letter-spacing: 0.16em;

            color: #666;
        }

        .eyebrow-line {
            width: 45px;
            height: 1px;

            background: #171717;
        }


        /* =====================================================
           MAIN NAME
        ===================================================== */

        .name {
            font-size: clamp(
                75px,
                13vw,
                205px
            );

            font-weight: 500;

            line-height: 0.78;

            letter-spacing: -0.085em;

            max-width: 1400px;
        }

        .name span {
            display: block;
        }

        .name .last-name {
            color: #777;
        }


        /* =====================================================
           LOWER HERO
        ===================================================== */

        .hero-lower {
            margin-top: 75px;

            display: grid;

            grid-template-columns:
                minmax(250px, 1fr)
                minmax(350px, 1.2fr);

            gap: 100px;

            align-items: end;
        }


        /* =====================================================
           DESCRIPTION
        ===================================================== */

        .description {
            max-width: 550px;

            font-size: clamp(
                22px,
                2.4vw,
                34px
            );

            line-height: 1.2;

            letter-spacing: -0.035em;
        }

        .description strong {
            font-weight: 500;
        }


        /* =====================================================
           BUTTONS
        ===================================================== */

        .actions {
            display: flex;
            gap: 12px;

            margin-top: 38px;

            flex-wrap: wrap;
        }

        .button {
            position: relative;

            display: inline-flex;

            align-items: center;
            justify-content: center;

            gap: 14px;

            min-width: 155px;

            padding: 16px 22px;

            border: 1px solid #171717;

            font-size: 13px;
            font-weight: 600;

            letter-spacing: 0.02em;

            overflow: hidden;

            transition:
                color 0.3s ease,
                transform 0.3s ease;
        }

        .button::before {
            content: "";

            position: absolute;

            inset: 0;

            background: #171717;

            transform: translateY(101%);

            transition:
                transform 0.3s ease;
        }

        .button span {
            position: relative;
            z-index: 2;
        }

        .button:hover {
            color: #fff;

            transform: translateY(-3px);
        }

        .button:hover::before {
            transform: translateY(0);
        }

        .arrow {
            transition: transform 0.3s ease;
        }

        .button:hover .arrow {
            transform: translateX(5px);
        }


        /* =====================================================
           RIGHT INFORMATION
        ===================================================== */

        .hero-info {
            border-top: 1px solid rgba(0,0,0,0.25);

            padding-top: 18px;

            display: grid;

            grid-template-columns: 1fr 1fr;

            gap: 35px;
        }

        .info-item small {
            display: block;

            margin-bottom: 9px;

            font-size: 10px;

            text-transform: uppercase;

            letter-spacing: 0.13em;

            color: #888;
        }

        .info-item p {
            font-size: 14px;
            line-height: 1.5;
        }


        /* =====================================================
           DECORATIVE NUMBER
        ===================================================== */

        .number {
            position: absolute;

            right: -15px;
            top: 48%;

            font-size: 12px;

            color: #999;

            writing-mode: vertical-rl;

            letter-spacing: 0.15em;
        }


        /* =====================================================
           BOTTOM BAR
        ===================================================== */

        .bottom-bar {
            position: absolute;

            bottom: 28px;

            left: 5%;
            right: 5%;

            display: flex;

            justify-content: space-between;

            align-items: center;

            font-size: 10px;

            text-transform: uppercase;

            letter-spacing: 0.14em;

            color: #888;
        }


        /* =====================================================
           ANIMATIONS
        ===================================================== */

        .fade-up {
            opacity: 0;

            transform: translateY(30px);

            animation:
                fadeUp 0.8s
                cubic-bezier(.2,.7,.2,1)
                forwards;
        }

        .delay-1 {
            animation-delay: 0.1s;
        }

        .delay-2 {
            animation-delay: 0.2s;
        }

        .delay-3 {
            animation-delay: 0.35s;
        }

        .delay-4 {
            animation-delay: 0.5s;
        }

        @keyframes fadeUp {

            to {
                opacity: 1;
                transform: translateY(0);
            }

        }


        /* =====================================================
           MOBILE
        ===================================================== */

        @media (max-width: 850px) {

            header {
                padding: 22px 6%;
            }

            .nav-right {
                display: none;
            }

            .hero {
                width: 88%;

                min-height: calc(100vh - 70px);

                padding:
                    70px 0
                    100px;
            }

            .name {
                font-size: 19vw;
            }

            .hero-lower {

                grid-template-columns: 1fr;

                gap: 55px;

                margin-top: 60px;
            }

            .hero-info {
                max-width: 600px;
            }

            .number {
                display: none;
            }

            .bottom-bar {
                display: none;
            }
        }


        @media (max-width: 500px) {

            .logo {
                font-size: 11px;
            }

            .eyebrow {
                font-size: 10px;
            }

            .name {
                font-size: 21vw;

                line-height: 0.82;
            }

            .description {
                font-size: 21px;
            }

            .actions {
                flex-direction: column;
                align-items: stretch;
            }

            .button {
                width: 100%;
            }

            .hero-info {
                grid-template-columns: 1fr;
                gap: 22px;
            }
        }

    </style>
</head>


<body>

<div class="page">


    <!-- ================= HEADER ================= -->

    <header>

        <nav>

            <div class="logo">
                KD
            </div>

            <div class="nav-right">

                <div class="status">
                    <span class="status-dot"></span>
                    Open to opportunities
                </div>

                <span>
                    Data · Analytics · BI
                </span>

            </div>

        </nav>

    </header>



    <!-- ================= HERO ================= -->

    <main>

        <section class="hero">

            <div class="hero-content">


                <!-- SMALL INTRO -->

                <div class="eyebrow fade-up">
                    <span class="eyebrow-line"></span>

                    Data Analyst · UK

                </div>



                <!-- NAME -->

                <h1 class="name fade-up delay-1">

                    <span>
                        Krishnapriya
                    </span>

                    <span class="last-name">
                        Doraiswamy
                    </span>

                </h1>



                <!-- LOWER CONTENT -->

                <div class="hero-lower">


                    <!-- LEFT -->

                    <div class="fade-up delay-2">

                        <p class="description">

                            I turn complex data into
                            <strong>clear insights,
                            reliable reporting</strong>
                            and better business decisions.

                        </p>


                        <!-- BUTTONS -->

                        <div class="actions">

                            <a
                                href="CV.pdf"
                                target="_blank"
                                class="button"
                            >

                                <span>
                                    View my CV
                                </span>

                                <span class="arrow">
                                    ↗
                                </span>

                            </a>


                            <a
                                href="mailto:your.email@example.com"
                                class="button"
                            >

                                <span>
                                    Contact me
                                </span>

                                <span class="arrow">
                                    ↗
                                </span>

                            </a>

                        </div>

                    </div>



                    <!-- RIGHT -->

                    <div class="fade-up delay-3">

                        <div class="hero-info">


                            <div class="info-item">

                                <small>
                                    Focus
                                </small>

                                <p>
                                    Data Analytics<br>
                                    Business Intelligence
                                </p>

                            </div>


                            <div class="info-item">

                                <small>
                                    Experience
                                </small>

                                <p>
                                    5+ years<br>
                                    Analytics & Data
                                </p>

                            </div>


                            <div class="info-item">

                                <small>
                                    Tools
                                </small>

                                <p>
                                    SQL · Python<br>
                                    Power BI · Tableau
                                </p>

                            </div>


                            <div class="info-item">

                                <small>
                                    Based
                                </small>

                                <p>
                                    United Kingdom
                                </p>

                            </div>


                        </div>

                    </div>

                </div>

            </div>



            <!-- DECORATIVE NUMBER -->

            <div class="number">
                01 / INTRODUCTION
            </div>



            <!-- BOTTOM -->

            <div class="bottom-bar">

                <span>
                    Scroll to explore
                </span>

                <span>
                    2026
                </span>

            </div>

        </section>

    </main>

</div>

</body>
</html>
