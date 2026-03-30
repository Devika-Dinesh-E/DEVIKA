<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Devika Dinesh E | Portfolio</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
}

body {
    background: #0a192f;
    color: #ccd6f6;
}

/* NAVBAR */
nav {
    display: flex;
    justify-content: space-between;
    padding: 20px 50px;
    background: #020c1b;
    position: sticky;
    top: 0;
}

nav h2 {
    color: #64ffda;
}

nav a {
    color: #ccd6f6;
    margin-left: 20px;
    text-decoration: none;
}

nav a:hover {
    color: #64ffda;
}

/* HERO */
.hero {
    height: 90vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding-left: 80px;
}

.hero h1 {
    font-size: 60px;
    color: #64ffda;
}

.hero p {
    font-size: 20px;
    margin-top: 10px;
}

/* SECTION */
section {
    padding: 80px;
}

h2 {
    color: #64ffda;
    margin-bottom: 20px;
}

/* ABOUT */
.about p {
    max-width: 800px;
    line-height: 1.8;
}

/* GRID */
.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

/* CARD */
.card {
    background: #112240;
    padding: 20px;
    border-radius: 10px;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}

/* SKILLS */
.skills span {
    display: inline-block;
    margin: 5px;
    padding: 8px 12px;
    background: #64ffda;
    color: #000;
    border-radius: 5px;
    font-size: 14px;
}

/* CONTACT */
.contact a {
    color: #64ffda;
    text-decoration: none;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 20px;
    background: #020c1b;
}
</style>

</head>
<body>

<!-- NAVBAR -->
<nav>
    <h2>Devika</h2>
    <div>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </div>
</nav>

<!-- HERO -->
<div class="hero">
    <h1>Devika Dinesh E</h1>
    <p>M.Tech | VLSI & Embedded Systems</p>
    <p>STM32 • PCB Design • IoT • Real-Time Systems</p>
</div>

<!-- ABOUT -->
<section id="about" class="about">
    <h2>About Me</h2>
    <p>
        M.Tech candidate specializing in VLSI and Embedded Systems with a keen interest in real-time applications, PCB design, and hardware-software co-development. Proficient in microcontroller programming, signal conditioning, and system-level circuit design for creating efficient electronic solutions. Driven to apply technical expertise and innovation in developing advanced embedded and VLSI projects.
    </p>
</section>

<!-- PROJECTS -->
<section id="projects">
    <h2>Projects</h2>

    <div class="grid">

        <div class="card">
            <h3>Solar Panel Emulator</h3>
            <p>STM32-based real-time solar panel emulator with PCB integrating converters and sensors.</p>
        </div>

        <div class="card">
            <h3>IoT Temperature System</h3>
            <p>STM32 + ESP8266 based temperature monitoring system with cloud connectivity.</p>
        </div>

        <div class="card">
            <h3>Railway Track Robot</h3>
            <p>IoT robot to detect cracks and send location data via mobile app.</p>
        </div>

        <div class="card">
            <h3>Heart Pulse Monitor</h3>
            <p>Real-time BPM monitoring system with alerts and IoT logging.</p>
        </div>

    </div>
</section>

<!-- SKILLS -->
<section id="skills">
    <h2>Skills</h2>

    <div class="skills">
        <span>Embedded C</span>
        <span>Verilog</span>
        <span>STM32</span>
        <span>Altium Designer</span>
        <span>Proteus</span>
        <span>LTspice</span>
        <span>Arduino</span>
        <span>SPI</span>
        <span>UART</span>
        <span>I2C</span>
    </div>
</section>

<!-- CONTACT -->
<section id="contact" class="contact">
    <h2>Contact</h2>
    <p>📞 +91 8089166527</p>
    <p>📧 devikadineshe8@gmail.com</p>
    <p>🔗 LinkedIn (add your link)</p>
</section>

<!-- FOOTER -->
<footer>
    <p>© 2026 Devika Dinesh E</p>
</footer>

</body>
</html>
