<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Prakhar Saikhedkar | Java Backend Developer</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: #f4f7fb;
            color: #1f2937;
            line-height: 1.6;
        }

        .container {
            width: 90%;
            max-width: 1100px;
            margin: auto;
        }

        /* Header */
        header {
            background: #111827;
            color: white;
            padding: 70px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 42px;
            margin-bottom: 10px;
        }

        header h2 {
            font-size: 22px;
            color: #60a5fa;
            font-weight: 500;
            margin-bottom: 20px;
        }

        header p {
            max-width: 750px;
            margin: auto;
            color: #d1d5db;
        }

        .contact {
            margin-top: 20px;
        }

        .contact a {
            color: #93c5fd;
            text-decoration: none;
            margin: 0 10px;
        }

        /* Sections */
        section {
            background: white;
            margin: 30px auto;
            padding: 35px;
            border-radius: 12px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.06);
        }

        section h2 {
            color: #111827;
            margin-bottom: 20px;
            border-bottom: 2px solid #2563eb;
            padding-bottom: 8px;
        }

        /* About */
        .about p {
            font-size: 17px;
        }

        /* Skills */
        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }

        .skill-card {
            background: #f8fafc;
            padding: 20px;
            border-radius: 10px;
            border-left: 4px solid #2563eb;
        }

        .skill-card h3 {
            margin-bottom: 10px;
            color: #2563eb;
        }

        /* Experience */
        .experience-item {
            margin-bottom: 30px;
        }

        .experience-item h3 {
            color: #111827;
        }

        .experience-item .company {
            color: #2563eb;
            font-weight: bold;
        }

        .experience-item .date {
            color: #6b7280;
            font-size: 14px;
            margin-bottom: 10px;
        }

        ul {
            padding-left: 20px;
        }

        li {
            margin-bottom: 8px;
        }

        /* Projects */
        .project {
            background: #f8fafc;
            padding: 25px;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .project h3 {
            color: #2563eb;
            margin-bottom: 8px;
        }

        .tech {
            font-size: 14px;
            color: #6b7280;
            margin-bottom: 12px;
        }

        /* Achievements */
        .achievement {
            background: #eff6ff;
            border-left: 5px solid #2563eb;
            padding: 15px;
            margin-bottom: 12px;
            border-radius: 5px;
        }

        /* Footer */
        footer {
            background: #111827;
            color: white;
            text-align: center;
            padding: 25px;
            margin-top: 40px;
        }

        /* Responsive */
        @media (max-width: 600px) {
            header h1 {
                font-size: 30px;
            }

            header h2 {
                font-size: 18px;
            }

            section {
                padding: 25px 20px;
            }
        }
    </style>
</head>

<body>

    <!-- Header -->
    <header>
        <div class="container">

            <h1>Prakhar Saikhedkar</h1>

            <h2>Java Backend Developer</h2>

            <p>
                Java Backend Developer with 4+ years of experience building
                scalable microservices, REST APIs, high-performance data
                processing systems, and cloud-based enterprise applications.
            </p>

            <div class="contact">
                <a href="tel:+916261348486">📞 +91-6261348486</a>
                <a href="mailto:saikhedkarprakhar@gmail.com">
                    ✉ saikhedkarprakhar@gmail.com
                </a>
                <span>📍 Hyderabad, India</span>
            </div>

        </div>
    </header>


    <main class="container">

        <!-- About -->
        <section class="about">

            <h2>Professional Profile</h2>

            <p>
                Java Backend Developer with 4+ years of professional experience
                across leading IT organizations, developing production-grade
                backend systems for global banking and insurance clients.
                Strong expertise in Java 8, Spring Boot, Microservices,
                REST APIs, AWS, JDBC, MySQL and multithreading.
            </p>

            <br>

            <p>
                Experienced in designing scalable data processing systems,
                optimizing application performance, conducting code reviews,
                managing CI/CD pipelines and collaborating with
                cross-functional Agile teams.
            </p>

        </section>


        <!-- Skills -->
        <section>

            <h2>Technical Skills</h2>

            <div class="skills">

                <div class="skill-card">
                    <h3>Languages & Frameworks</h3>
                    <p>
                        Java 8, Spring Boot, Hibernate, Microservices,
                        REST APIs, Servlets, JSP
                    </p>
                </div>

                <div class="skill-card">
                    <h3>Cloud & DevOps</h3>
                    <p>
                        AWS, CI/CD, GitHub, Bitbucket, Redis
                    </p>
                </div>

                <div class="skill-card">
                    <h3>Database</h3>
                    <p>
                        MySQL, JDBC
                    </p>
                </div>

                <div class="skill-card">
                    <h3>Testing & Libraries</h3>
                    <p>
                        JUnit, Apache PDFBox, Log4j
                    </p>
                </div>

                <div class="skill-card">
                    <h3>Core Concepts</h3>
                    <p>
                        Multithreading, OOP, Data Structures & Algorithms,
                        Agile/Scrum
                    </p>
                </div>

            </div>

        </section>


        <!-- Experience -->
        <section>

            <h2>Professional Experience</h2>

            <div class="experience-item">

                <h3>Packaged App Development Senior Analyst</h3>

                <div class="company">Accenture</div>

                <div class="date">
                    March 2026 – Present | Hyderabad, Telangana
                </div>

                <ul>
                    <li>
                        Building scalable Java/Spring Boot microservices and
                        RESTful APIs for enterprise clients.
                    </li>

                    <li>
                        Conducting code reviews and collaborating with
                        cross-functional teams to maintain clean architecture
                        and coding standards.
                    </li>

                    <li>
                        Managing deployments through CI/CD pipelines and
                        cloud platforms for reliable production releases.
                    </li>
                </ul>

            </div>


            <div class="experience-item">

                <h3>System Engineer</h3>

                <div class="company">Tata Consultancy Services</div>

                <div class="date">
                    July 2022 – February 2026 | Pune, Maharashtra
                </div>

                <ul>
                    <li>
                        Designed and delivered Java-based data processing and
                        migration systems for global banking and insurance
                        clients.
                    </li>

                    <li>
                        Used Java 8, Spring Boot, JDBC and REST APIs with
                        AWS deployments.
                    </li>

                    <li>
                        Resolved critical performance bottlenecks using
                        multithreading and parallel query execution,
                        reducing processing time by 15%.
                    </li>

                    <li>
                        Built a high-throughput framework processing
                        1 million+ records daily across four parallel SQL
                        threads.
                    </li>

                    <li>
                        Conducted PR reviews and merge approvals while
                        enforcing clean architecture and coding standards.
                    </li>
                </ul>

            </div>

        </section>


        <!-- Projects -->
        <section>

            <h2>Key Projects</h2>


            <div class="project">

                <h3>TD Bank – 1-Click Project</h3>

                <div class="tech">
                    Java 8 | Spring Boot | Apache PDFBox |
                    Microservices | AWS | Log4j
                </div>

                <ul>
                    <li>
                        Developed a Java utility for parsing and validating
                        insurance policy data using Apache PDFBox.
                    </li>

                    <li>
                        Designed and deployed Spring Boot microservices on AWS
                        for secure policy data storage and retrieval.
                    </li>

                    <li>
                        Optimized key data handling bottlenecks and improved
                        system stability during peak business hours.
                    </li>

                    <li>
                        Produced stakeholder validation reports for data
                        transparency.
                    </li>
                </ul>

            </div>


            <div class="project">

                <h3>Deutsche Bank – Data Migration Framework</h3>

                <div class="tech">
                    Java 8 | Spring Boot | JDBC | MySQL |
                    REST APIs | AWS
                </div>

                <ul>
                    <li>
                        Engineered a high-performance Spring Boot framework
                        for database data migration.
                    </li>

                    <li>
                        Implemented Java multithreading to execute four SQL
                        queries in parallel.
                    </li>

                    <li>
                        Reduced migration time by 15% while processing
                        1 million+ records daily.
                    </li>

                    <li>
                        Built RESTful APIs for upstream and downstream
                        system integration.
                    </li>
                </ul>

            </div>

        </section>


        <!-- Education -->
        <section>

            <h2>Education</h2>

            <div class="experience-item">

                <h3>Bachelor of Technology – Computer Science</h3>

                <div class="company">
                    Shri Vaishnav Vidyapeeth Vishwavidyalaya
                </div>

                <div class="date">
                    August 2018 – June 2022 | Indore, Madhya Pradesh
                </div>

            </div>

        </section>


        <!-- Achievements -->
        <section>

            <h2>Achievements</h2>

            <div class="achievement">
                🏆 Client Appreciation Award – TD Bank 1-Click Project
            </div>

            <div class="achievement">
                🏆 TCS On-the-Spot Award – Outstanding contribution
                and key role in project delivery
            </div>

        </section>

    </main>


    <!-- Footer -->
    <footer>

        <p>
            © 2026 Prakhar Saikhedkar | Java Backend Developer
        </p>

    </footer>

</body>
</html>
