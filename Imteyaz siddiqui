<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Md Imteyaz Sheikh | Professional Portfolio</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --accent-color: #e74c3c;
            --light-color: #ecf0f1;
            --dark-color: #2c3e50;
            --text-color: #333;
            --text-light: #777;
            --max-width: 1200px;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            line-height: 1.6;
            color: var(--text-color);
            background-color: #f9f9f9;
        }

        a {
            text-decoration: none;
            color: var(--secondary-color);
        }

        .container {
            width: 100%;
            max-width: var(--max-width);
            margin: 0 auto;
            padding: 0 20px;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: var(--secondary-color);
            color: white;
            border-radius: 5px;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            font-weight: 600;
        }

        .btn:hover {
            background-color: #2980b9;
            transform: translateY(-2px);
        }

        section {
            padding: 80px 0;
        }

        .section-title {
            text-align: center;
            margin-bottom: 60px;
            font-size: 2.5rem;
            color: var(--primary-color);
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background-color: var(--secondary-color);
            margin: 15px auto;
        }

        /* Header */
        header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: fixed;
            width: 100%;
            z-index: 100;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary-color);
        }

        .nav-links {
            display: flex;
            list-style: none;
        }

        .nav-links li {
            margin-left: 30px;
        }

        .nav-links a {
            color: var(--text-color);
            font-weight: 500;
            transition: color 0.3s ease;
        }

        .nav-links a:hover {
            color: var(--secondary-color);
        }

        .hamburger {
            display: none;
            cursor: pointer;
        }

        /* Hero Section */
        #hero {
            height: 100vh;
            display: flex;
            align-items: center;
            background: linear-gradient(135deg, rgba(52, 152, 219, 0.1) 0%, rgba(231, 76, 60, 0.1) 100%);
            padding-top: 80px;
        }

        .hero-content {
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 50px;
        }

        .hero-text {
            flex: 1;
        }

        .hero-text h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            color: var(--primary-color);
        }

        .hero-text h2 {
            font-size: 1.5rem;
            margin-bottom: 20px;
            color: var(--text-light);
            font-weight: 400;
        }

        .hero-text p {
            margin-bottom: 30px;
            font-size: 1.1rem;
            max-width: 600px;
        }

        .hero-image {
            flex: 1;
            text-align: center;
        }

        .hero-image img {
            width: 100%;
            max-width: 400px;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        /* About Section */
        #about {
            background-color: white;
        }

        .about-content {
            display: flex;
            align-items: center;
            gap: 50px;
        }

        .about-image {
            flex: 1;
            text-align: center;
        }

        .about-image img {
            width: 100%;
            max-width: 400px;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        .about-text {
            flex: 1;
        }

        .about-text h3 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: var(--primary-color);
        }

        .about-text p {
            margin-bottom: 20px;
        }

        /* Skills Section */
        #skills {
            background-color: #f5f5f5;
        }

        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .skill-card {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease;
        }

        .skill-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }

        .skill-card h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: var(--primary-color);
        }

        .skill-card p {
            margin-bottom: 15px;
        }

        .skill-items {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 20px;
        }

        .skill-item {
            background-color: var(--light-color);
            color: var(--primary-color);
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
        }

        /* Projects Section */
        #projects {
            background-color: white;
        }

        .projects-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .project-card {
            background-color: #f5f5f5;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }

        .project-image {
            width: 100%;
            height: 200px;
            overflow: hidden;
        }

        .project-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }

        .project-card:hover .project-image img {
            transform: scale(1.1);
        }

        .project-info {
            padding: 20px;
        }

        .project-info h3 {
            font-size: 1.3rem;
            margin-bottom: 10px;
            color: var(--primary-color);
        }

        .project-info p {
            margin-bottom: 15px;
            color: var(--text-light);
        }

        .project-links {
            display: flex;
            gap: 15px;
        }

        .project-links a {
            font-size: 0.9rem;
        }

        /* Contact Section */
        #contact {
            background-color: #f5f5f5;
        }

        .contact-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 50px;
        }

        .contact-info h3 {
            font-size: 1.5rem;
            margin-bottom: 20px;
            color: var(--primary-color);
        }

        .contact-info p {
            margin-bottom: 30px;
        }

        .contact-items {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        .contact-item {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .contact-icon {
            width: 50px;
            height: 50px;
            background-color: var(--light-color);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--secondary-color);
            font-size: 1.2rem;
        }

        .contact-form {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: 500;
        }

        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 10px 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
        }

        .form-group textarea {
            min-height: 150px;
            resize: vertical;
        }

        /* Footer */
        footer {
            background-color: var(--primary-color);
            color: white;
            text-align: center;
            padding: 30px 0;
        }

        .footer-content {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .social-links {
            display: flex;
            gap: 20px;
            margin-bottom: 20px;
        }

        .social-link {
            width: 40px;
            height: 40px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            transition: all 0.3s ease;
        }

        .social-link:hover {
            background-color: var(--secondary-color);
            transform: translateY(-3px);
        }

        .copyright {
            font-size: 0.9rem;
            opacity: 0.7;
        }

        /* Responsive Styles */
        @media (max-width: 992px) {
            .hero-content,
            .about-content {
                flex-direction: column;
            }

            .hero-text,
            .about-text {
                text-align: center;
                padding: 20px 0;
            }

            .hero-image,
            .about-image {
                order: -1;
            }

            .section-title {
                font-size: 2rem;
            }

            .hero-text h1 {
                font-size: 2.5rem;
            }
        }

        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }

            .hamburger {
                display: block;
            }

            .section-title {
                font-size: 1.8rem;
                margin-bottom: 40px;
            }

            .hero-text h1 {
                font-size: 2rem;
            }

            .hero-text h2 {
                font-size: 1.2rem;
            }

            section {
                padding: 60px 0;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <nav>
                <div class="logo">Md Imteyaz</div>
                <ul class="nav-links">
                    <li><a href="#hero">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
                <div class="hamburger">
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="hero">
        <div class="container">
            <div class="hero-content">
                <div class="hero-text">
                    <h1>Hi, I'm Md Imteyaz Sheikh</h1>
                    <h2>Professional Software Developer</h2>
                    <p>I specialize in creating beautiful, functional, and user-friendly digital experiences. My passion lies in solving complex problems with elegant solutions that drive results.</p>
                    <a href="#contact" class="btn">Get In Touch</a>
                </div>
                <div class="hero-image">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/e8e30607-f7d2-4b91-ad58-7296848203e3.png" alt="Professional headshot of Md Imteyaz Sheikh smiling in formal attire against a neutral background" />
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2 class="section-title">About Me</h2>
            <div class="about-content">
                <div class="about-image">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/3d9aeb65-1825-4e36-b8ee-6189c6edc30a.png" alt="Md Imteyaz Sheikh working on a laptop in a cozy home office setting with plants and books in the background" />
                </div>
                <div class="about-text">
                    <h3>Who I Am</h3>
                    <p>I'm a passionate developer with over 5 years of experience in building web applications. My journey in technology began when I was just starting college, and since then I've been fascinated by the power of code to create impactful solutions.</p>
                    <p>What sets me apart is my ability to combine technical expertise with creative problem-solving. I believe that great software should not only function well but also provide a delightful user experience.</p>
                    <p>When I'm not coding, you can find me exploring new technologies, contributing to open-source projects, or mentoring junior developers.</p>
                    <a href="#" class="btn">Download CV</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <div class="container">
            <h2 class="section-title">My Skills</h2>
            <div class="skills-container">
                <div class="skill-card">
                    <h3>Frontend Development</h3>
                    <p>Creating beautiful, responsive interfaces with modern web technologies.</p>
                    <div class="skill-items">
                        <span class="skill-item">HTML5</span>
                        <span class="skill-item">CSS3</span>
                        <span class="skill-item">JavaScript</span>
                        <span class="skill-item">React</span>
                        <span class="skill-item">Vue.js</span>
                        <span class="skill-item">SASS</span>
                    </div>
                </div>
                <div class="skill-card">
                    <h3>Backend Development</h3>
                    <p>Building robust server-side applications and APIs for various business needs.</p>
                    <div class="skill-items">
                        <span class="skill-item">Node.js</span>
                        <span class="skill-item">Express</span>
                        <span class="skill-item">Python</span>
                        <span class="skill-item">Django</span>
                        <span class="skill-item">MongoDB</span>
                        <span class="skill-item">PostgreSQL</span>
                    </div>
                </div>
                <div class="skill-card">
                    <h3>Other Skills</h3>
                    <p>Additional competencies that complement my development skills.</p>
                    <div class="skill-items">
                        <span class="skill-item">Git</span>
                        <span class="skill-item">Docker</span>
                        <span class="skill-item">AWS</span>
                        <span class="skill-item">CI/CD</span>
                        <span class="skill-item">Agile</span>
                        <span class="skill-item">UI/UX</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <div class="container">
            <h2 class="section-title">My Projects</h2>
            <div class="projects-container">
                <div class="project-card">
                    <div class="project-image">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/7ce35682-669d-40d4-b624-5a75a37df7d6.png" alt="Dashboard interface of an e-commerce analytics platform showing sales metrics and charts" />
                    </div>
                    <div class="project-info">
                        <h3>E-commerce Dashboard</h3>
                        <p>A comprehensive analytics dashboard for online stores with real-time reporting capabilities.</p>
                        <div class="project-links">
                            <a href="#" class="btn">View Demo</a>
                            <a href="#">Code</a>
                        </div>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/62b366e1-75bd-49aa-a714-64dabd6afbe1.png" alt="Mobile app interface for a fitness tracking application with workout statistics" />
                    </div>
                    <div class="project-info">
                        <h3>Fitness Tracker App</h3>
                        <p>A mobile application that helps users track their workouts, nutrition, and fitness goals.</p>
                        <div class="project-links">
                            <a href="#" class="btn">View Demo</a>
                            <a href="#">Code</a>
                        </div>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/8fae002e-00d7-4167-9bde-4b6da7c3fa67.png" alt="Collaborative document editing tool with multiple users editing the same document" />
                    </div>
                    <div class="project-info">
                        <h3>Collaborative Editor</h3>
                        <p>Real-time collaborative document editing platform with version control and commenting.</p>
                        <div class="project-links">
                            <a href="#" class="btn">View Demo</a>
                            <a href="#">Code</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <div class="contact-content">
                <div class="contact-info">
                    <h3>Let's Work Together</h3>
                    <p>I'm always interested in hearing about new projects and opportunities. Feel free to contact me for collaboration or just to say hi!</p>
                    <div class="contact-items">
