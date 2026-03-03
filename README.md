<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />

<title>Horizontal Section Website</title>

<style>
    /* RESET */
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: Arial, sans-serif;
    }

    html {
        scroll-behavior: smooth;
    }

    body {
        background: #f5f5f5;
    }

    /* NAVBAR */
    nav {
        position: fixed;
        top: 0;
        width: 100%;
        background: #222;
        padding: 15px;
        text-align: center;
        z-index: 1000;
    }

    nav a {
        color: white;
        margin: 0 20px;
        text-decoration: none;
        font-weight: bold;
        transition: 0.3s;
    }

    nav a:hover {
        color: #ffcc00;
    }

    /* SECTION */
    section {
        padding-top: 100px;
        min-height: 100vh;
        text-align: center;
    }

    .title {
        font-size: 2.5rem;
        margin-bottom: 20px;
    }

    /* IMAGE SPACE */
    .image {
        width: 100%;
        height: 350px;
        background-size: cover;
        background-position: center;
    }

    /* DIFFERENT IMAGES */
    #home .image {
        background-image: url("https://picsum.photos/1600/800?1");
    }

    #about .image {
        background-image: url("https://picsum.photos/1600/800?2");
    }

    #projects .image {
        background-image: url("https://picsum.photos/1600/800?3");
    }

    #contact .image {
        background-image: url("https://picsum.photos/1600/800?4");
    }

    /* TEXT */
    .content {
        padding: 30px;
        max-width: 900px;
        margin: auto;
        font-size: 1.1rem;
        line-height: 1.6;
    }
</style>
</head>

<body>

<!-- NAVIGATION -->
<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<!-- SECTION 1 -->
<section id="home">
    <div class="title">Home</div>
    <div class="image"></div>
    <div class="content">
        Welcome to the website. This section introduces the main idea.
    </div>
</section>

<!-- SECTION 2 -->
<section id="about">
    <div class="title">About</div>
    <div class="image"></div>
    <div class="content">
        Information about the company or person goes here.
    </div>
</section>

<!-- SECTION 3 -->
<section id="projects">
    <div class="title">Projects</div>
    <div class="image"></div>
    <div class="content">
        Showcase your work, portfolio, or gallery here.
    </div>
</section>

<!-- SECTION 4 -->
<section id="contact">
    <div class="title">Contact</div>
    <div class="image"></div>
    <div class="content">
        Contact details, email, or form can be placed here.
    </div>
</section>

</body>
</html>
