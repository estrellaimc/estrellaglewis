<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estrella G. Lewis | Portfolio</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Playfair Display', serif;
        }

        body {
            background: #000;
            color: #ffd020;
            text-align: center;
        }

        /* Navbar */
        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            padding: 20px 0;
            background: #bd1d30;
        }

        nav a {
            color: #ffd020;
            text-decoration: none;
            font-weight: bold;
            letter-spacing: 1px;
            transition: 0.3s;
        }

        nav a:hover {
            text-shadow: 0 0 10px #ffd020;
        }

        /* Hero Section */
        .hero {
            height: 80vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background: url('https://source.unsplash.com/1600x900/?stars,galaxy') no-repeat center center/cover;
            text-shadow: 0px 0px 15px rgba(255, 208, 32, 0.6);
        }

        .hero h1 {
            font-size: 4rem;
            text-transform: uppercase;
            font-weight: 900;
        }

        .hero p {
            font-size: 1.2rem;
            margin-top: 10px;
        }

        /* Remove default link styles & keep text gold */
.grid-container a {
    text-decoration: none; /* Removes underline */
    color: #ffd020; /* Keeps text gold */
    transition: 0.3s;
}

/* Hover effect - subtle glow */
.grid-container a:hover {
    text-shadow: 0 0 10px #ffd020;
}

        .grid-item {
            background: #111;
            padding: 20px;
            border-radius: 10px;
            transition: 0.3s;
        }

        .grid-item:hover {
            transform: scale(1.05);
            box-shadow: 0 0 15px #ffd020;
        }

        .grid-item img {
            max-width: 100%;
            border-radius: 10px;
        }

        /* Footer */
        .footer {
            padding: 20px;
            background: #bd1d30;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .footer a {
            color: #ffd020;
            text-decoration: none;
            font-size: 1.5rem;
            transition: 0.3s;
        }

        .footer a:hover {
            text-shadow: 0 0 10px #ffd020;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <nav>
    <a href="/about">About</a>
    <a href="/campaignexamples">Campaign Examples</a>
    <a href="/casestudies">Case Studies</a>
    <a href="/podcasts">Podcasts</a>
    <a href="/connect">Connect with me (like actually)!</a>
    <a href="/starstuff">Star Stuff</a>
</nav>


    <!-- Hero Section -->
    <section class="hero">
        <h1>Estrella G. Lewis</h1>
        <p>Integrated Marketing Communications Student | Cosmic Strategist</p>
    </section>

 <!-- About Section -->
<section id="about" class="grid-container">
    <div class="grid-item" onclick="window.location.href='/about'">
        <img src="https://i.imgur.com/OHMAbBi.png" alt="The Hummingbird Approach" width="200">
        <h2>About Me</h2>
        <p>"The Hummingbird Approach"</p>
    </div>
</section>

<!-- Work Grid -->
<section id="work" class="grid-container">
    <div class="grid-item" onclick="window.location.href='/campaignexamples'">
        <img src="https://i.imgur.com/IL4xA61.png" alt="Campaign Examples">
        <h3>Campaign Examples</h3>
        <p>What would I do?</p>
    </div>

    <div class="grid-item" onclick="window.location.href='/casestudies'">
        <img src="https://i.imgur.com/3stGjvi.png" alt="Case Studies" width="200">
        <h3>Case Studies</h3>
        <p>Projects from my academic journey.</p>
    </div>
</section>

    <!-- Podcast Section -->
    <section id="podcasts" class="grid-container">
        <div class="grid-item">
            <h2>Podcasts<br><br></h2>
            <iframe style="border-radius:12px" src="https://open.spotify.com/embed/show/0h2tNfDOJpwQ9zkqIlnkcL?utm_source=generator" width="100%" height="152" frameBorder="0"></iframe>
        </div>
    </section>

    <!-- Contact -->
    <footer class="footer">
        <a href="https://www.linkedin.com/in/estrellaglewis" target="_blank">LinkedIn</a>
        <a href="mailto:egarcialewis5836@sdsu.edu">Gmail</a>
    </footer>

</body>
</html>
