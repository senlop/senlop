<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav ul {
            padding: 0;
            list-style: none;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        .main-content {
            padding: 20px;
            background: #fff;
            margin-top: 20px;
            border-radius: 8px;
        }
        .main-content h2 {
            color: #333;
        }
        .section {
            margin-bottom: 20px;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: absolute;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>John Doe</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <div class="container main-content">
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>Hello! I'm John Doe, a web developer with a passion for creating engaging and dynamic web experiences. With a background in both front-end and back-end development, I enjoy solving complex problems and building intuitive interfaces.</p>
        </section>

        <section id="skills" class="section">
            <h2>Skills</h2>
            <ul>
                <li>HTML, CSS, JavaScript</li>
                <li>React, Node.js</li>
                <li>Python, Django</li>
            </ul>
        </section>

        <section id="projects" class="section">
            <h2>Projects</h2>
            <div>
                <h3>Project One</h3>
                <p>A brief description of the project, what technologies were used, and what the project accomplishes.</p>
            </div>
            <div>
                <h3>Project Two</h3>
                <p>A brief description of the project, what technologies were used, and what the project accomplishes.</p>
            </div>
        </section>

        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>Email: john.doe@example.com</p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/johndoe" target="_blank">linkedin.com/in/johndoe</a></p>
            <p>GitHub: <a href="https://github.com/johndoe" target="_blank">github.com/johndoe</a></p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 John Doe. All rights reserved.</p>
    </footer>
</body>
</html>
