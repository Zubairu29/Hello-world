<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>YELWA GLOBAL RESOURCES</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Roboto', sans-serif; }
    body { line-height: 1.6; color: #333; background-color: #f4f4f4; }
    header { background: #0077b6; color: #fff; padding: 20px 0; text-align: center; }
    header h1 { margin-bottom: 10px; }
    nav { margin-top: 10px; }
    nav a { color: #fff; margin: 0 15px; text-decoration: none; font-weight: bold; }
    nav a:hover { text-decoration: underline; }
    section { padding: 60px 20px; max-width: 1100px; margin: auto; }
    .services, .contact { background: #fff; border-radius: 8px; padding: 40px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); }
    .services h2, .contact h2 { margin-bottom: 20px; text-align: center; color: #0077b6; }
    .service-item { margin-bottom: 20px; }
    .contact form { display: flex; flex-direction: column; }
    .contact input, .contact textarea { padding: 10px; margin-bottom: 15px; border: 1px solid #ccc; border-radius: 4px; }
    .contact button { padding: 10px; background: #0077b6; color: #fff; border: none; border-radius: 4px; cursor: pointer; }
    .contact button:hover { background: #005f87; }
    footer { background: #023e8a; color: #fff; text-align: center; padding: 20px; margin-top: 40px; }
  </style>
</head>
<body>

<header>
  <h1>YELWA GLOBAL RESOURCES</h1>
  <p>Technology | Verification | Web Design | Sidra Cafe</p>
  <nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="home">
  <h2>Welcome to YELWA GLOBAL RESOURCES</h2>
  <p>We provide top-notch solutions in technology verification, web design, and more. Our goal is to empower businesses and individuals with reliable, innovative services. Explore our offerings below and get in touch with us today!</p>
</section>

<section id="services" class="services">
  <h2>Our Services</h2>
  <div class="service-item">
    <h3>Technology Verification</h3>
    <p>We ensure your technology solutions are authentic, secure, and optimized for performance. Our verification process guarantees reliability and trust.</p>
  </div>
  <div class="service-item">
    <h3>Sidra Cafe Support</h3>
    <p>Offering digital and operational support for Sidra Cafe, from management tools to online promotions.</p>
  </div>
  <div class="service-item">
    <h3>Web Design & Development</h3>
    <p>Custom websites that are modern, responsive, and visually appealing. Perfect for businesses, portfolios, and e-commerce.</p>
  </div>
</section>

<section id="contact" class="contact">
  <h2>Contact Us</h2>
  <form>
    <input type="text" name="name" placeholder="Your Name" required>
    <input type="email" name="email" placeholder="Your Email" required>
    <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
    <button type="submit">Send Message</button>
  </form>
</section>

<footer>
  <p>&copy; 2025 YELWA GLOBAL RESOURCES. All Rights Reserved.</p>
</footer>

</body>
</html>
