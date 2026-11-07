<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Mpho Raat's personal portfolio website">
    <title>Mpho Raat | Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <nav>
            <h1>Mpho Raat</h1>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#recommendations">Recommendations</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <img src="https://placehold.co/200x200"
                 alt="Placeholder profile image for Mpho Raat">
            <p>Hello! My name is Mpho Raat. Welcome to my personal portfolio.
               I am interested in technology, learning and developing new skills.</p>
        </section>

        <section id="skills">
            <h2>My Skills</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>Problem Solving</li>
            </ul>
        </section>

        <section id="projects">
            <h2>My Projects</h2>
            <article>
                <h3>Portfolio Website</h3>
                <p>A personal website created using HTML, CSS and JavaScript.</p>
            </article>
            <article>
                <h3>Web Development Practice</h3>
                <p>Projects completed while learning web development.</p>
            </article>
        </section>

        <section id="recommendations">
            <h2>Recommendations</h2>
            <div id="recommendation-list">
                <p>Welcome to my portfolio!</p>
            </div>

            <h3>Leave a Recommendation</h3>
            <form id="recommendation-form">
                <label for="recommendation">Your recommendation:</label>
                <textarea id="recommendation" required></textarea>
                <button type="submit">Submit</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Mpho Raat. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
