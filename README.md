<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="STC Aerospace - Precision Aerospace Manufacturing">
    <title>STC Aerospace</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background: linear-gradient(90deg, #0056b3, #002663);
            color: white;
            padding: 1rem 0;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }

        header h1 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        header nav {
            text-align: center;
            margin-top: 0.5rem;
        }

        header nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1.2rem;
        }

        header nav a:hover {
            text-decoration: underline;
        }

        .hero {
            background: url('hero-image.jpg') no-repeat center center/cover;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }

        .hero h2 {
            font-size: 3rem;
        }

        section {
            padding: 2rem 0;
            background: white;
            margin-bottom: 1rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1rem;
        }

        .grid div {
            padding: 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            text-align: center;
            background: #f9f9f9;
        }

        footer {
            text-align: center;
            padding: 1rem;
            background: #002663;
            color: white;
        }

        footer p {
            font-size: 0.9rem;
        }

        .button {
            display: inline-block;
            padding: 0.8rem 1.5rem;
            margin-top: 1rem;
            background: #0056b3;
            color: white;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
        }

        .button:hover {
            background: #003d99;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>STC Aerospace</h1>
            <nav>
                <a href="#about">About</a>
                <a href="#services">Services</a>
                <a href="#capabilities">Capabilities</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <div class="hero">
        <h2>Precision Aerospace Manufacturing</h2>
    </div>

    <div class="container">
        <section id="about">
            <h2>About Us</h2>
            <p>STC Aerospace specializes in precision machining and complex assembly operations for the aerospace industry. With a commitment to excellence, we deliver high-quality products that meet AS9100 standards.</p>
        </section>

        <section id="services">
            <h2>Our Services</h2>
            <div class="grid">
                <div>
                    <h3>Precision Machining</h3>
                    <p>We offer cutting-edge machining services using advanced CNC technology.</p>
                </div>
                <div>
                    <h3>Riveting & Assembly</h3>
                    <p>Expert riveting and assembly services to meet complex aerospace requirements.</p>
                </div>
                <div>
                    <h3>Quality Assurance</h3>
                    <p>AS9100-certified processes ensure unmatched quality in every product.</p>
                </div>
            </div>
        </section>

        <section id="capabilities">
            <h2>Capabilities</h2>
            <p>Our facilities feature advanced equipment including:</p>
            <ul>
                <li>3 Five-Axis CNC Machines</li>
                <li>6 Three-Axis CNC Machines</li>
                <li>2 Horizontal Machining Centers</li>
                <li>3 High-Precision Lathes</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>Have questions? Reach out to us for more information or to request a quote.</p>
            <a href="mailto:info@stcaero.com" class="button">Contact Us</a>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 STC Aerospace. All Rights Reserved.</p>
    </footer>
</body>
</html>
