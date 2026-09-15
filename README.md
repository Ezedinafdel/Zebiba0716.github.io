<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ezedin Afdel | Personal Portfolio</title>

    <meta name="description"
          content="Personal portfolio of Ezedin Afdel - technology, AI and digital solutions.">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background: #f5f7fb;
            color: #222;
        }

        header {
            background: #111827;
            color: white;
            padding: 20px 8%;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 25px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #60a5fa;
        }

        .hero {
            min-height: 90vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(135deg, #111827, #2563eb);
            color: white;
        }

        .hero h1 {
            font-size: 50px;
            margin-bottom: 15px;
        }

        .hero h2 {
            font-size: 25px;
            margin-bottom: 20px;
            font-weight: normal;
        }

        .hero p {
            max-width: 650px;
            margin: auto;
            font-size: 18px;
        }

        .btn {
            display: inline-block;
            margin-top: 30px;
            padding: 13px 25px;
            background: white;
            color: #2563eb;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
        }

        section {
            padding: 70px 8%;
        }

        section h2 {
            text-align: center;
            margin-bottom: 35px;
            font-size: 32px;
            color: #111827;
        }

        .about {
            max-width: 850px;
            margin: auto;
            text-align: center;
            font-size: 18px;
        }

        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 20px;
            max-width: 900px;
            margin: auto;
        }

        .skill {
            background: white;
            padding: 25px;
            text-align: center;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            font-weight: bold;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .project {
            background: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
        }

        .project h3 {
            margin-bottom: 10px;
            color: #2563eb;
        }

        .contact {
            text-align: center;
            background: #e5e7eb;
        }

        .contact a {
            color: #2563eb;
            text-decoration: none;
            font-weight: bold;
        }

        footer {
            background: #111827;
            color: white;
            text-align: center;
            padding: 25px;
        }

        @media (max-width: 700px) {
            nav {
                flex-direction: column;
                gap: 15px;
            }

            nav ul {
                gap: 12px;
                flex-wrap: wrap;
                justify-content: center;
            }

            .hero h1 {
                font-size: 38px;
            }

            .hero h2 {
                font-size: 21px;
            }
        }
    </style>
</head>

<body>

<header>
    <nav>
        <div class="logo">Ezedin Afdel</div>

        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section class="hero" id="home">
    <div>
        <h1>Hello, I'm Ezedin Afdel</h1>

        <h2>Technology & Digital Solutions</h2>

        <p>
            Welcome to my personal portfolio. I am interested in
            technology, artificial intelligence, web development,
            and creating useful digital solutions.
        </p>

        <a class="btn" href="#contact">Contact Me</a>
    </div>
</section>

<section id="about">
    <h2>About Me</h2>

    <div class="about">
        <p>
            I am Ezedin Afdel, a technology enthusiast interested in
            building practical digital solutions and learning modern
            technologies. This portfolio showcases my skills,
            projects, and professional interests.
        </p>
    </div>
</section>

<section id="skills">
    <h2>My Skills</h2>

    <div class="skills">
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">Web Development</div>
        <div class="skill">Artificial Intelligence</div>
        <div class="skill">GitHub</div>
    </div>
</section>

<section id="projects">
    <h2>My Projects</h2>

    <div class="projects">

        <div class="project">
            <h3>Personal Portfolio</h3>
            <p>
                A responsive personal portfolio website created
                using HTML and CSS and hosted with GitHub Pages.
            </p>
        </div>

        <div class="project">
            <h3>AI Projects</h3>
            <p>
                Exploring artificial intelligence and practical
                AI-powered digital solutions.
            </p>
        </div>

        <div class="project">
            <h3>Web Development</h3>
            <p>
                Building simple, responsive and user-friendly
                websites using modern web technologies.
            </p>
        </div>

    </div>
</section>

<section class="contact" id="contact">
    <h2>Contact Me</h2>

    <p>
        Email:
        <a href="mailto:ezuyebaba7ezuyebaba7@gmail.com">
            ezuyebaba7ezuyebaba7@gmail.com
        </a>
    </p>

    <p>
        GitHub:
        <a href="https://github.com/Zebiba0716" target="_blank">
            github.com/Zebiba0716
        </a>
    </p>
</section>

<footer>
    <p>© 2026 Ezedin Afdel. All rights reserved.</p>
</footer>

</body>
</html>
