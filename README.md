# portfolio.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="header">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSPlvnAePsFPE4njnjtHcVdPmjw2K7G7cCbqw&s" alt="your image"  class="">
        <h1 class="name">SHRAVYA KUPPALA</h1>
        <p class="intro">Welcome to my portfolio! I am a  web developer.</p>
    </header>
    <main class="main-content">
        <section class="about">
            <h2>About Me</h2>
            <p>Looking for the position of a computer engineer to work in competitive and fast-paced conditions that will help me evovle as an individual and a working professional while also letting me contribute to the company's overall growth.</p>
        </section>
        <section class="projects">
            <h2>Projects</h2>
            <ul>
                <li>Game developing - Awarded with a participation certificate in SEEKH conducted in GLWEC.</li>
            </ul>
        </section>
        <section class="contact">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:your-email@example.com">patelshravya359@gmail.com</a></p>
            <p>Phone: <a href="tel:+1234567890">9100813255</a></p>
        </section>
    </main>
    <footer class="footer">
        <p>© 2024 Shravya. All rights reserved.</p>
    </footer>
</body>
</html>

#portfolio.css

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    color: #333;
    background-color: #f4f4f9;
}

.header {
    text-align: center;
    padding: 2rem;
    background-color: #4CAF50;
    color: white;
}

.profile-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 1rem;
}

.name {
    font-size: 2.5rem;
    margin: 0.5rem 0;
}

.intro {
    font-size: 1.2rem;
    margin: 0.5rem 0 0;
}

.main-content {
    padding: 2rem;
    max-width: 800px;
    margin: 0 auto;
}

section {
    margin-bottom: 2rem;
}

h2 {
    color: #4CAF50;
    margin-bottom: 1rem;
}

ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    margin: 0.5rem 0;
    background: #e0f7fa;
    padding: 0.5rem;
    border-radius: 5px;
}

.contact a {
    color: #4CAF50;
    text-decoration: none;
}

.contact a:hover {
    text-decoration: underline;
}

.footer {
    text-align: center;
    padding: 1rem;
    background-color: #333;
    color: white;
}
