
<!DOCTYPE html>

<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: hsla(288, 95%, 15%, 0.909);
            color: white;
            display: flex;
            flex-direction: column;
            min-height: 100vh; 
        }

        header {
            background: violet;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 10px;
        }

        nav a {
            color: rgb(4, 39, 12);
            text-decoration: none;
            padding: 10px;
            border-radius: 5px;
            background: pink;
            transition: background 0.3s ease;
        }

        nav a:hover {
            background: yellow;
        }

        section {
            padding: 40px;
            margin: 20px 0;
            background-color: rgba(183, 108, 237, 0.793);
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .about img {
            max-width: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        .about, .skills, .projects, .contact {
            text-align: center;
        }

        h2 {
            color: white;
        }

        .skills ul, .projects ul {
            list-style: none;
            padding: 0;
        }

        .skills li, .projects li {
            display: inline-block;
            margin: 10px;
            padding: 10px;
            background-color: burlywood;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .contact a {
            color: white;
            text-decoration: none;
        }

        footer {
            background: violet;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: auto; /* Pushes the footer to the bottom */
        }
    </style>
</head>
<body>

    <header>
        <h1>My Portfolio</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about" class="about">
        <img src="C:\Users\HP\Downloads\WhatsApp Image 2025-01-11 at 10.10.28 PM.jpeg" alt="My Photo"> 
        <h2>About Me</h2>
        <P>MYSELF OJASWI ASALKAR</P>
        <p> I'm in progressing to improve my skills.<br>I'm a active learner with a strong work ethic and a dedication to produce high-quality work.<br>
        </p>
    </section>

    <section id="my background" class="my background">
        <h2>My Background</h2>
        <ul>
            <li>I'm from Science background with Biology subject in Junior college.</li>
            <li>But, I'm eager to learn and expand my knowledge to build a strong foundation in Artificial Intelligence and Data Science.
            </li>
        </ul>
    </section>
    <section id="skills" class="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>Python</li>
            <li>DBMS</li>
        
        </ul>
    </section>

    <section id="projects" class="projects">
        <h2>Projects</h2>
        <ul>
            <li>
                <h3>Portfolio Website</h3>
                <p>Built with HTML and CSS</p>
            </li>
            <li>
                <h3>E-commerce website</h3>
                <p>Built with connecting HTML and CSS</p>
            </li>
            <li>
                <h3>NUMBER GUESSING GAME</h3>
                <p>Developed with C</p>
            </li>
            <li>
                <h3>WORD COUNTER</h3>
                <p>Developed with Python</p>
            </li>
        </ul>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <p>Feel free to reach out to me!</p>
        <p>Email: <a href="mailto:your-email@example.com">ojaswiasalkar@gmail.com</a></p>
        <p>Phone: 9404380615</p>
    </section>

    <footer>
        <p>© 2025 OJASWI ASALKAR</p>
    </footer>



</body></html>


