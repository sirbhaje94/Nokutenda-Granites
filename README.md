<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Nokutenda Granites</title>
    <style>
        body { 
            font-family: Arial, sans-serif; 
            background: #ECECEC; 
            margin: 0; 
            padding: 0; 
        }
        header, footer { 
            background: #333; 
            color: #fff; 
            text-align: center; 
            padding: 1.5em 0; 
        }
        nav { 
            background: #444; 
            color: #fff; 
            padding: 0.8em; 
            text-align: center; 
        }
        nav a { 
            color: #fff; 
            margin: 0 20px; 
            text-decoration: none; 
            font-weight: bold;
        }
        section { 
            padding: 2em; 
            max-width: 900px; 
            margin: auto; 
        }
        .logo {
            font-size: 2.5em;
            font-weight: bold;
            letter-spacing: 2px;
            color: #555;
            background: linear-gradient(90deg, #888, #333 80%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 0.2em;
        }
        .granite-bar {
            height: 8px;
            width: 160px;
            margin: 0.5em auto 1em auto;
            background: repeating-linear-gradient(
                45deg, #888, #888 10px, #333 10px, #333 20px
            );
            border-radius: 4px;
        }
        ul { padding-left: 1.4em; }
        label { display: block; margin-top: 1em; }
        input, textarea { width: 100%; padding: 0.5em; margin-top: 0.2em; border-radius: 4px; border: 1px solid #ccc;}
        input[type="submit"] { background: #333; color: #fff; border: none; cursor: pointer; width: auto; padding: 0.6em 2em;}
        .contact-info { line-height: 2; }
        .socials a { color: #444; font-weight: bold; }
        .map-container { margin: 2em 0; text-align: center; }
        @media (max-width: 600px) {
            section { padding: 1em; }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Nokutenda Granites</div>
        <div class="granite-bar"></div>
        <p>Your Trusted Granite Supplier</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home">
        <h2>Welcome to Nokutenda Granites</h2>
        <p>We provide high-quality granite for construction, decoration, and masonry work. Our products are both durable and beautiful, perfect for any project.</p>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Nokutenda Granites is located at the corner of Golden Quarry and Bulawayo Road, opposite the Museum. We are dedicated to supplying premium granite with excellent service and competitive pricing. Our team is experienced in both supply and installation, ensuring customer satisfaction for every project.</p>
        <ul>
            <li><strong>Location:</strong> cnr Golden Quarry and Bulawayo Rd, opposite Museum</li>
            <li><strong>Business Hours:</strong> 07:00 – 17:30</li>
            <li><strong>Phone/WhatsApp:</strong> <a href="tel:+263718506422">0718 506 422</a></li>
            <li><strong>Facebook:</strong> <a href="https://facebook.com/graniteandmasonry" target="_blank">granite and masonry</a></li>
        </ul>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Granite supply and delivery</li>
            <li>Custom granite cutting and fabrication</li>
            <li>Granite installation for kitchens, bathrooms, and more</li>
            <li>Masonry and stonework services</li>
            <li>Consultation and site measurement</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <div class="contact-info">
            <p><strong>Address:</strong> cnr Golden Quarry and Bulawayo Rd, opposite Museum</p>
            <p><strong>Phone/WhatsApp:</strong> <a href="tel:+263718506422">0718 506 422</a></p>
            <p><strong>Email:</strong> <a href="mailto:nokutendagranites@github.com">nokutendagranites@github.com</a></p>
            <p><strong>Facebook Page:</strong> <a href="https://facebook.com/graniteandmasonry" target="_blank">granite and masonry</a></p>
            <p><strong>Business Hours:</strong> 07:00 – 17:30</p>
        </div>
        <form name="contact" method="POST" data-netlify="true">
            <label>Name:
                <input type="text" name="name" required>
            </label>
            <label>Email:
                <input type="email" name="email" required>
            </label>
            <label>Message:
                <textarea name="message" rows="5" required></textarea>
            </label>
            <input type="submit" value="Send Message">
        </form>
        <div class="map-container">
            <h3>Find Us Here:</h3>
            <iframe
                src="https://www.google.com/maps?q=-17.829222,31.049225&z=17&output=embed"
                width="100%" height="250" frameborder="0" style="border:0;"
                allowfullscreen="" aria-hidden="false" tabindex="0">
            </iframe>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Nokutenda Granites. All rights reserved.</p>
    </footer>
</body>
</html>