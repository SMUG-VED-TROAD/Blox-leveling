<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Blox Leveling</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    html, body {
      height: 100%;
      margin: 0;
      padding: 0;
    }body {
  font-family: 'Roboto', sans-serif;
  background-image: url('https://yourdomain.com/path-to-image.jpg');
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
  color: #000000;
}

header {
  background-color: rgba(0, 0, 0, 0.7);
  color: #ffffff;
  text-align: center;
  padding: 2rem 1rem 1rem;
  font-weight: bold;
  font-size: 2.5rem;
  letter-spacing: 1px;
}

.logo {
  max-width: 120px;
  margin: 0 auto 1rem;
  display: block;
}

nav {
  margin-top: 10px;
}

nav a {
  margin: 0 15px;
  color: #ffcc00;
  text-decoration: none;
  font-weight: 700;
}

.section {
  padding: 2rem;
  text-align: center;
}

.section h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.packages-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
}

.package {
  min-width: 220px;
  min-height: 220px;
  padding: 1rem;
  border-radius: 50%;
  background: linear-gradient(to bottom right, #00008b, #00ffff);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #ffffff;
  font-weight: bold;
  font-size: 1rem;
  box-sizing: border-box;
  border: 3px solid #000000;
  transition: transform 0.3s, background-color 0.3s;
}

.package:hover {
  transform: scale(1.08);
}

.description {
  font-style: italic;
  font-size: 0.95rem;
  display: block;
  margin-top: 0.3rem;
  margin-bottom: 0.3rem;
}

.price {
  font-size: 1.1rem;
  font-weight: bold;
}

footer {
  background-color: #000000;
  color: #ffffff;
  text-align: center;
  padding: 1.5rem;
  font-size: 0.9rem;
}

.disclaimer {
  font-weight: bold;
  font-size: 0.75rem;
  color: #000000;
  background-color: #000000;
  padding: 0.5rem;
  margin: 1rem auto;
  max-width: 700px;
  border-radius: 8px;
}

.contact-info {
  color: magenta;
  font-size: 1.1rem;
  margin: 0.5rem 0;
  font-style: italic;
}

a {
  color: magenta;
  text-decoration: underline;
}

.gradient-box {
  background: linear-gradient(to right, #00008b, #00ffff);
  padding: 1rem;
  margin: 2rem auto;
  max-width: 600px;
  border-radius: 8px;
  border: 3px solid #000000;
  color: #ffffff;
  font-weight: bold;
}

  </style>
</head>
<body>
  <header>
    <img class="logo" src="https://static.wikia.nocookie.net/roblox-blox-fruits/images/5/5e/BloxFruits_Logo.png" alt="Blox Fruits Logo">
    BLOX LEVELING
    <nav>
      <a href="#services">Services</a>
      <a href="#how">How It Works</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>  <section class="section" id="services">
    <h2>Our Packages</h2>
    <div class="packages-container">
      <div class="package">1st Sea Cleared<br><span class="description">700 Level</span><span class="price">100₹</span></div>
      <div class="package">1st Sea + All Gear<br><span class="description">All accessories & weapons</span><span class="price">150₹</span></div>
      <div class="package">2nd Sea Cleared<br><span class="description">1500 Level</span><span class="price">200₹</span></div>
      <div class="package">2nd Sea + All Gear<br><span class="description">Accessories & weapons</span><span class="price">250₹</span></div>
      <div class="package">3rd Sea Cleared<br><span class="description">Max level (current update)</span><span class="price">300₹</span></div>
      <div class="package">3rd Sea + All Gear<br><span class="description">All accessories & weapons</span><span class="price">350₹</span></div>
    </div>
  </section>  <section class="section" id="how">
    <div class="gradient-box">
      <h2>How It Works</h2>
      <p class="description">1. Choose your desired package</p>
      <p class="description">2. Contact us and provide Roblox account info</p>
      <p class="description">3. We boost your account fast & securely</p>
      <p class="description">4. Receive your account with upgraded stats</p>
    </div>
  </section>  <section class="section" id="contact">
    <div class="gradient-box">
      <h2>Contact Us</h2>
      <p class="contact-info">Email: <a href="mailto:BloxLeveling@gmail.com">BloxLeveling@gmail.com</a></p>
      <p class="contact-info">Payments: Phone Pe,Google Pay,Any upi</p>
  </section>  <footer>
    <p class="disclaimer">⚠️ This service is not affiliated with Roblox or Blox Fruits. Account sharing may violate Roblox's Terms of Service. Use at your own risk.</p>
    <p>&copy; 2025 Blox Leveling. All rights reserved.</p>
  </footer>
</body>
</html>
