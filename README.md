# GadgetmanGH.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tiguer Sound | Professional Audio Engineering</title>
    <meta name="description" content="Premium mixing, mastering, recording, and sound design services based in New York. Over 15 years delivering world-class audio for artists, labels, film, and brands.">
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg: #0a0a0a;
            --accent: #00ff9d; /* Electric teal/green for highlights */
            --text: #e0e0e0;
            --text-light: #aaaaaa;
            --dark-gray: #1e1e1e;
        }
        * { margin:0; padding:0; box-sizing:border-box; }
        body {
            font-family: 'Inter', sans-serif;
            background: var(--bg);
            color: var(--text);
            line-height: 1.6;
            overflow-x: hidden;
        }
        header {
            height: 100vh;
            min-height: 600px;
            background: linear-gradient(rgba(10,10,10,0.8), rgba(10,10,10,0.9)), url('hero-background.jpg') center/cover no-repeat fixed; /* Replace with your own dark abstract waveform or studio photo */
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            position: relative;
        }
        .logo {
            font-family: 'Orbitron', sans-serif;
            font-size: 5rem;
            font-weight: 700;
            color: white;
            text-shadow: 0 0 20px var(--accent);
            margin-bottom: 1rem;
        }
        .tagline {
            font-size: 1.8rem;
            color: var(--accent);
            letter-spacing: 2px;
            margin-bottom: 2rem;
        }
        .cta {
            padding: 15px 40px;
            background: transparent;
            border: 2px solid var(--accent);
            color: var(--accent);
            font-size: 1.1rem;
            cursor: pointer;
            transition: all 0.4s;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        .cta:hover {
            background: var(--accent);
            color: black;
            box-shadow: 0 0 30px rgba(0,255,157,0.5);
        }
        section { padding: 100px 10%; }
        h2 {
            font-family: 'Orbitron', sans-serif;
            font-size: 3.5rem;
            text-align: center;
            margin-bottom: 60px;
            color: white;
            position: relative;
        }
        h2::after {
            content: '';
            width: 100px;
            height: 3px;
            background: var(--accent);
            position: absolute;
            bottom: -20px;
            left: 50%;
            transform: translateX(-50%);
        }
        #about, #services, #clients { background: var(--dark-gray); }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .card {
            background: rgba(255,255,255,0.03);
            padding: 30px;
            border-radius: 10px;
            border: 1px solid rgba(0,255,157,0.2);
            transition: transform 0.4s;
        }
        .card:hover { transform: translateY(-10px); }
        .card h3 {
            color: var(--accent);
            margin-bottom: 15px;
            font-size: 1.5rem;
        }
        ul { list-style: none; }
        li {
            padding: 8px 0;
            position: relative;
            padding-left: 25px;
        }
        li::before {
            content: '▸';
            color: var(--accent);
            position: absolute;
            left: 0;
        }
        #contact {
            text-align: center;
            background: var(--bg);
        }
        #contact a {
            color: var(--accent);
            text-decoration: none;
            font-size: 1.5rem;
        }
        footer {
            text-align: center;
            padding: 40px;
            background: black;
            color: var(--text-light);
            font-size: 0.9rem;
        }
        @media (max-width: 768px) {
            .logo { font-size: 3.5rem; }
            .tagline { font-size: 1.4rem; }
            h2 { font-size: 2.8rem; }
        }
    </style>
</head>
<body>

    <header id="home">
        <div>
            <h1 class="logo">TIGUER SOUND</h1>
            <p class="tagline">World-Class Audio Engineering • New York</p>
            <button class="cta" onclick="document.getElementById('contact').scrollIntoView({behavior: 'smooth'});">Get In Touch</button>
        </div>
    </header>

    <section id="about">
        <h2>About</h2>
        <div class="grid">
            <div class="card">
                <p>Tiguer Sound is a premium audio engineering studio led by award-winning engineer <strong>Dave Tiguer</strong>. With over 15 years in the industry, we specialize in delivering radio-ready mixes, masters, and productions for independent artists, major labels, film, TV, and advertising.</p>
                <br>
                <p>From platinum-selling records to Grammy-nominated projects, our obsessive attention to detail and cutting-edge techniques guarantee your music sounds massive on every system.</p>
            </div>
        </div>
    </section>

    <section id="services">
        <h2>Services</h2>
        <div class="grid">
            <div class="card">
                <h3>Mixing</h3>
                <ul>
                    <li>Stereo & Dolby Atmos mixing</li>
                    <li>Stem mixing</li>
                    <li>Vocal tuning & alignment</li>
                    <li>Analog summing available</li>
                </ul>
            </div>
            <div class="card">
                <h3>Mastering</h3>
                <ul>
                    <li>High-end analog & digital mastering</li>
                    <li>Mastered for Streaming (Apple, Spotify, etc.)</li>
                    <li>Vinyl & CD prep</li>
                    <li>DDP & reference masters</li>
                </ul>
            </div>
            <div class="card">
                <h3>Recording & Production</h3>
                <ul>
                    <li>Full tracking sessions</li>
                    <li>Sound design & beat production</li>
                    <li>Podcast production</li>
                    <li>Voiceover & ADR</li>
                </ul>
            </div>
        </div>
    </section>

    <section id="clients">
        <h2>Selected Clients & Credits</h2>
        <div class="grid" style="text-align:center; font-size:1.2rem; color:var(--text-light);">
            <div>Universal Music • Sony • Warner • Netflix • HBO • Adidas • Independent Artists Worldwide</div>
            <!-- Add more or replace with your actual clients -->
        </div>
    </section>

    <section id="contact">
        <h2>Let's Work Together</h2>
        <p style="font-size:1.5rem; margin:40px 0;">hello@tiguersound.com<br>
        <a href="mailto:hello@tiguersound.com">hello@tiguersound.com</a></p>
        <p>New York City • Available Worldwide</p>
    </section>

    <footer>
        © 2025 Tiguer Sound. All rights reserved.
    </footer>

</body>
</html>
