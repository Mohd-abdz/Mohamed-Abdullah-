<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohamed Abdullah- Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #8BC34A;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #d32f2f;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }
        nav a:hover {
            background: #b71c1c;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
            background: white;
        }
        h2 {
            color: #d32f2f;
        }
        ul {
            list-style-type: none;
        }
        .btn {
            display: inline-block;
            background: black;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            margin-top: 10px;
        }
        .btn:hover {
            background: grey;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #333;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    Mohamed Abdullah<br>
    <small>Student </small>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#resume">Resume</a>
</nav>

<div class="container">
    <section id="about">
        <h2>About Me</h2>
        <p>I'm a <strong>computer science student</strong> mohamed Abdullah,2 years computer science student.</p>
    </section>

    <section id="education">
        <h2>Education</h2>
        <p><strong>University of madras</strong> - computer science </p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Python</li>
            <li>Machine Learning & AI</li>
            <li>Java</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li><a href="#">AI-Based Alternator Control System</a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
        </ul>
    </section>

    <section id="resume">
        <h2>Resume</h2>
        <a href="your_resume.pdf" download class="btn">Download CV</a>
    </section>
</div>

<footer>
    &copy; 2025 Mohamed Abdullah 
</footer>

</body>
</html>
