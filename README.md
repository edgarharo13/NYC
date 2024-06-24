<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edgar's Creative Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
            font-family: 'Copperplate', 'Papyrus', fantasy;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 15px 20px;
            text-decoration: none;
            text-transform: uppercase;
            font-weight: bold;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        section {
            padding: 50px 0;
        }
        section h2 {
            font-family: 'Copperplate', 'Papyrus', fantasy;
            font-size: 2em;
            text-align: center;
            margin-bottom: 20px;
        }
        .about, .contact {
            background-color: #fff;
            padding: 40px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .about p, .contact p {
            font-size: 1.2em;
            line-height: 1.6;
        }
        .projects, .gallery, .blog {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .projects .project, .gallery .image, .blog .post {
            flex: 1 1 calc(33.333% - 40px);
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .projects .project img, .gallery .image img {
            max-width: 100%;
            height: auto;
        }
        .blog .post h3 {
            margin-top: 0;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
        @media (max-width: 768px) {
            .projects .project, .gallery .image, .blog .post {
                flex: 1 1 calc(50% - 40px);
            }
        }
        @media (max-width: 480px) {
            .projects .project, .gallery .image, .blog .post {
                flex: 1 1 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Edgar's Creative Portfolio</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#gallery">Gallery</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about" class="about">
            <h2>About Me</h2>
            <p>Hi, I'm Edgar Haro, a 31-year-old Californian living in New York City. After a tumultuous childhood and upbringing, I am proof that it gets better. I am living an incredible life, filled with hope and endless possibilities. Welcome to my creative portfolio where I showcase my projects, memories, and experiences.</p>
        </section>
        <section id="projects" class="projects">
            <h2>Projects</h2>
            <div class="project">
                <img src="64E17859-64F0-43CF-BD10-7D3CD64C87D2_1_105_c.jpeg" alt="Project 1">
                <h3>Project Title 1</h3>
                <p>Brief description of the project.</p>
            </div>
            <div class="project">
                <img src="project2.jpg" alt="Project 2">
                <h3>Project Title 2</h3>
                <p>Brief description of the project.</p>
            </div>
            <div class="project">
                <img src="project3.jpg" alt="Project 3">
                <h3>Project Title 3</h3>
                <p>Brief description of the project.</p>
            </div>
        </section>
        <section id="gallery" class="gallery">
            <h2>Gallery</h2>
            <div class="image">
                <img src="memory1.jpg" alt="Memory 1">
            </div>
            <div class="image">
                <img src="memory2.jpg" alt="Memory 2">
            </div>
            <div class="image">
                <img src="memory3.jpg" alt="Memory 3">
            </div>
        </section>
        <section id="blog" class="blog">
            <h2>Blog</h2>
            <div class="post">
                <h3>Blog Post Title 1</h3>
                <p>Summary or excerpt of the blog post.</p>
            </div>
            <div class="post">
                <h3>Blog Post Title 2</h3>
                <p>Summary or excerpt of the blog post.</p>
            </div>
            <div class="post">
                <h3>Blog Post Title 3</h3>
                <p>Summary or excerpt of the blog post.</p>
            </div>
        </section>
        <section id="contact" class="contact">
            <h2>Contact Me</h2>
            <p>If you'd like to get in touch, feel free to email me at: <a href="mailto:edgar@example.com">edgar@example.com</a></p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Edgar Haro. All Rights Reserved.</p>
    </footer>
</body>
</html>
