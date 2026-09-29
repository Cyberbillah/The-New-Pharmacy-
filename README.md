# The-New-Pharmacy-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The New Pharmacy</title>
    <style>
        /* General styling and colors */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0fdf4;
            color: #333;
        }
        header {
            background-color: #166534;
            color: white;
            padding: 2rem 1rem;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            margin: 10px 0 0;
            font-size: 1.2rem;
            opacity: 0.9;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #14532d;
        }
        nav a {
            color: white;
            padding: 15px 20px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            background-color: #166534;
        }
        .container {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }
        .section-title {
            color: #166534;
            border-bottom: 2px solid #166534;
            padding-bottom: 5px;
        }
        .service-card {
            background: white;
            padding: 20px;
            margin-bottom: 15px;
            border-radius: 8px;
            border-left: 5px solid #166534;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .service-card h3 {
            margin-top: 0;
            color: #166534;
        }
        footer {
            text-align: center;
            padding: 15px;
            background-color: #166534;
            color: white;
            margin-top: 20px;
        }
        
        /* Mobile-friendly adjustments */
        @media (max-width: 600px) {
            nav {
                flex-direction: column;
                text-align: center;
            }
            header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>The New Pharmacy</h1>
        <p>Your Health, Our Priority</p>
    </header>

    <nav>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact Us</a>
    </nav>

    <div class="container">
        <section id="about">
            <h2 class="section-title">Welcome</h2>
            <p>At <strong>The New Pharmacy</strong>, we are dedicated to providing the highest quality healthcare products and prescription services to our community. Our goal is to ensure you get fast, reliable, and caring service every time you visit.</p>
        </section>

        <section id="services">
            <h2 class="section-title">Our Services</h2>
            
            <div class="service-card">
                <h3>💊 Prescription Refills</h3>
                <p>Fast, accurate, and safe prescription processing. Drop off your prescription and let us handle the rest.</p>
            </div>
            
            <div class="service-card">
                <h3>🩺 Over-the-Counter Medicine</h3>
                <p>A wide variety of everyday health and wellness products, from vitamins to pain relief.</p>
            </div>
            
            <div class="service-card">
                <h3>🩹 Medical Supplies</h3>
                <p>Essential first aid items, home care equipment, and personal hygiene products.</p>
            </div>
        </section>

        <section id="contact">
            <h2 class="section-title">Contact & Location</h2>
            <div class="service-card">
                <p><strong>📍 Address:</strong> [Add your shop address here]</p>
                <p><strong>📞 Phone:</strong> [Add your phone number here]</p>
                <p><strong>⏰ Hours:</strong> 8:00 AM - 10:00 PM (Open 7 Days a week)</p>
            </div>
        </section>
    </div>

    <footer>
        &copy; 2026 The New Pharmacy. All Rights Reserved.
    </footer>

</body>
</html>
