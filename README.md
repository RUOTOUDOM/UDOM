<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Portfolio</title>
    <!-- CSS Styles -->
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
        }

        /* Header */
        header {
            background-color: #261414;
            color: rgb(153, 92, 92);
            text-align: center;
            padding: 1rem 0;
            font-family: Arial;
        }

        header h1 {
            margin-bottom: 0.5rem;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1.1rem;
        }

        /* About Section */
        .about {
            text-align: center;
            padding: 2rem;
            background-color: #f4f4f4;
        }

        .about img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            margin-bottom: 1rem;
        }

        /* Skills Section */
        .skills {
            padding: 2rem;
            text-align: center;
        }

        .skills ul {
            list-style: none;
        }

        .skills li {
            display: inline-block;
            background-color: #007BFF;
            color: white;
            padding: 0.5rem 1rem;
            margin: 0.5rem;
            border-radius: 5px;
            font-style: calc();
        }

        /* Contact Section */
        .contact {
            text-align: center;
            padding: 2rem;
            background-color: #f4f4f4;
        }

        .contact a {
            display: inline-block;
            color: white;
            background-color: #333;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 5px;
        }

        footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 1rem 0;
            margin-top: 1rem;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <a href="#about">AbouT Me</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- About Section -->
    <section id="about" class="about">
        <img src="photo_2024-12-17_23-09-16.jpg" alt="My Photo">
        <h2>About Me</h2>
        <p aria-flowto="">Hello! My name is <strong>Udom</strong>. I am studying <strong>Computer Science</strong> and I live in <strong>Toul Sdey Village, Toul Sdey Commune, Chantrea District, Svay Rieng Province</strong>. I am proud to be a farmer's son, and my passion for learning and technology drives me forward every day.</p>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <h2>My Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>Responsive Design</li>
        </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <p>If you'd like to work with me, feel free to reach out:</p>
        <a href="khg0489@gmail.com">Email Me</a>
        <a href="0714595435">Phone Me</a>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Udom..</p>
    </footer>
</body>
</html>
