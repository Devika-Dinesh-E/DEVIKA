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
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #071a2f;
            color: #ffffff;
            line-height: 1.6;
        }

        section {
            padding: 60px 20px;
            max-width: 1000px;
            margin: auto;
        }

        h1, h2 {
            color: #4ef0c0;
        }

        h2 {
            border-bottom: 2px solid #4ef0c0;
            display: inline-block;
            margin-bottom: 20px;
        }

        /* HERO */
        .hero {
            text-align: center;
            padding: 100px 20px;
        }

        .hero h1 {
            font-size: 48px;
        }

        .hero p {
            margin-top: 10px;
        }

        /* CARDS */
        .card {
            background: #0c2a4a;
            padding: 20px;
            margin-top: 20px;
            border-radius: 10px;
        }

        /* SKILLS */
        .skills span {
            display: inline-block;
            background: #4ef0c0;
            color: #000;
            padding: 5px 10px;
            margin: 5px;
            border-radius: 5px;
            font-size: 14px;
        }

        /* CONTACT */
        .contact a {
            color: #4ef0c0;
            text-decoration: none;
        }

    </style>

</head>
<body>

    <!-- HERO -->
    <section class="hero">
        <h1>Devika Dinesh E</h1>
        <p>M.Tech VLSI & Embedded Systems</p>
        <p>STM32 | PCB Design | IoT | Real-Time Systems</p>
    </section>

    <!-- ABOUT -->
    <section>
        <h2>About</h2>
        <p>
            M.Tech candidate specializing in VLSI and Embedded Systems with a keen interest in real-time applications, PCB design, and hardware-software co-development. Proficient in microcontroller programming, signal conditioning, and system-level circuit design for creating efficient electronic solutions. Driven to apply technical expertise and innovation in developing advanced embedded and VLSI projects.
        </p>
    </section>

    <!-- EDUCATION -->
    <section>
        <h2>Education</h2>

        <div class="card">
            <h3>M.Tech – VLSI and Embedded Systems</h3>
            <p>Mar Athanasius College of Engineering (2024–2026)</p>
            <p>CGPA: 8.07</p>
        </div>

        <div class="card">
            <h3>B.Tech – Electronics and Communication</h3>
            <p>Vimal Jyothi Engineering College (2020–2024)</p>
            <p>CGPA: 8.59</p>
        </div>

    </section>

    <!-- SKILLS -->
    <section>
        <h2>Skills</h2>

        <div class="skills">
            <span>Embedded C</span>
            <span>Verilog</span>
            <span>C Programming</span>
            <span>STM32</span>
            <span>Altium Designer</span>
            <span>Proteus</span>
            <span>LTspice</span>
            <span>Arduino IDE</span>
            <span>SPI</span>
            <span>UART</span>
            <span>I2C</span>
        </div>

    </section>

    <!-- EXPERIENCE -->
    <section>
        <h2>Experience</h2>

        <div class="card">
            <h3>Embedded Systems Internship</h3>
            <p>CSEED – June 2025</p>
            <p>
                Worked on STM32 interfacing with sensors, Bluetooth, Wi-Fi, and NodeMCU communication. Gained exposure to RTOS and real-time scheduling.
            </p>
        </div>

    </section>

    <!-- PROJECTS -->
    <section>
        <h2>Projects</h2>

        <div class="card">
            <h3>Solar Panel Emulator (STM32)</h3>
            <p>
                Designed a real-time solar panel emulator with PCB integrating STM32, converters, and sensors for renewable energy applications.
            </p>
        </div>

        <div class="card">
            <h3>IoT Temperature Monitoring System</h3>
            <p>
                Developed PCB using STM32 + ESP8266 for real-time cloud-based temperature monitoring.
            </p>
        </div>

        <div class="card">
            <h3>Railway Track Inspecting Robot</h3>
            <p>
                IoT-based robot to detect track cracks and provide location data via Android app.
            </p>
        </div>

        <div class="card">
            <h3>Heart Pulse Monitoring System</h3>
            <p>
                Built a pulse monitoring system with BPM display and alert system with optional IoT logging.
            </p>
        </div>

    </section>

    <!-- CONTACT -->
    <section class="contact">
        <h2>Contact</h2>
        <p>📞 +91 8089166527</p>
        <p>📧 devikadineshe8@gmail.com</p>
        <p>🔗 <a href="#">LinkedIn Profile</a></p>
    </section>

</body>
</html>
