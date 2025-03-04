<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MBH Express - Reliable Trucking Solutions</title>
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

        header {
            background-color: #2c3e50;
            color: white;
            padding: 1rem;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo img {
            height: 50px;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            margin-left: 2rem;
        }

        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('truck-bg.jpg');
            background-size: cover;
            background-position: center;
            height: 80vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            margin-top: 60px;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            max-width: 1200px;
            margin: 2rem auto;
            padding: 2rem;
        }

        .service-card {
            background: white;
            padding: 2rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            text-align: center;
        }

        .section {
            padding: 4rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .contact-container, .join-team {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 2rem;
            margin-top: 2rem;
        }

        .card {
            background: #f9f9f9;
            padding: 2rem;
            border-radius: 5px;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 4rem;
        }

        .btn-primary {
            background-color: #e67e22;
            color: white;
            padding: 1rem 2rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <img src="HBM Express PNG.png" alt="MBH Express Logo">
            </div>
            <div class="nav-links">
                <a href="#home">Home</a>
                <a href="#services">Services</a>
                <a href="#join-team">Join Our Team</a>
                <a href="#contact">Contact</a>
            </div>
        </nav>
    </header>

    <section class="hero" id="home">
        <div class="hero-content">
            <h1>Professional Freight Services</h1>
            <p>24/7 Transportation Solutions Across North America</p>
            <a href="#contact" class="btn-primary">Get Free Quote</a>
        </div>
    </section>

    <section class="services" id="services">
        <div class="services-grid">
            <div class="service-card">
                <h3>Dry Van Shipping</h3>
                <p>Secure general freight transportation with temperature-controlled options</p>
            </div>
            <div class="service-card">
                <h3>Refrigerated Transport</h3>
                <p>Temperature-controlled logistics for perishable goods</p>
            </div>
        </div>
    </section>

    <section class="section" id="join-team">
        <h2 class="text-center">Join Our Team</h2>
        <div class="join-team">
            <div class="card">
                <h3>Why Drive With Us?</h3>
                <ul>
                    <li>Competitive pay & benefits</li>
                    <li>Modern equipment</li>
                    <li>24/7 driver support</li>
                </ul>
            </div>
            <div class="card">
                <a href="https://intelliapp.driverapponline.com/c/mbhexpressinc?uri_b=ia_mbhexpressinc_1951082259" 
                   class="btn-primary" 
                   target="_blank"
                   style="display: block; text-align: center;">
                    Apply Now
                </a>
                <p style="text-align: center; margin-top: 1rem;">Opens in new window</p>
            </div>
        </div>
    </section>

    <section class="section" id="contact">
        <h2 class="text-center">Contact Us</h2>
        <div class="contact-container">
            <div class="card">
                <h3>Contact Information</h3>
                <p>
                    <strong>Address:</strong><br>
                    7895 Broadway, Suite G Room D<br>
                    Merrillville, IN 46410<br>
                    USA
                </p>
                <p><strong>Phone:</strong> 219-200-2109</p>
                <p><strong>Email:</strong> safety@mbhexpress.com</p>
            </div>
            <form class="card">
                <h3>Send Message</h3>
                <input type="text" placeholder="Name" style="width: 100%; margin: 1rem 0; padding: 0.5rem;">
                <input type="email" placeholder="Email" style="width: 100%; margin: 1rem 0; padding: 0.5rem;">
                <textarea placeholder="Message" style="width: 100%; height: 150px; margin: 1rem 0; padding: 0.5rem;"></textarea>
                <button type="submit" class="btn-primary">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 MBH Express. All rights reserved.</p>
    </footer>
</body>
</html>
