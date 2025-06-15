
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Charity: Water - Make Waves</title>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      font-family: 'DM Sans', sans-serif;
      background-color: white;
    }

    .navbar {
      background-color: #fff;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 2px solid #f3b600;
    }

    .navbar .logo {
      display: flex;
      align-items: center;
      gap: 10px;
      font-weight: bold;
      font-size: 1.5rem;
      color: #003366;
    }

    .navbar .logo img {
      width: 30px;
      height: 30px;
    }

    .navbar nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #003366;
      font-weight: 500;
    }

    .navbar nav a:hover {
      text-decoration: underline;
    }

<img class="top-image" src="photo water fam/water-well.jpg" alt="Community gathering at water well" />

    .top-image {
  width: 100%;
  height: auto;
  display: block;
  margin: 0 auto;
}

    .hero-text {
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
      background-color: #f3b600;
      color: #990000;
      padding: 40px 20px;
      font-size: 3rem;
      font-weight: bold;
      line-height: 1.2;
      animation: slideUp 1.5s ease-out;
      text-align: center;
    }

    .cta-container {
      background-color: #f3b600;
      padding: 40px 20px;
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      gap: 20px;
      animation: fadeIn 2s ease-in;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 10px;
      font-size: 1.5rem;
      font-weight: bold;
    }

    .brand-logo {
      background-color: #f3b600;
      border-radius: 5px;
      padding: 5px;
      font-weight: bold;
    }

    .cta-message {
      font-size: 1.2rem;
      color: #003366;
      max-width: 500px;
    }

    .cta-button {
      background-color: #002f6c;
      color: white;
      font-size: 1rem;
      font-weight: bold;
      padding: 15px 25px;
      border-radius: 30px;
      text-decoration: none;
      display: inline-block;
    }

    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: auto;
      animation: fadeIn 2s ease-in;
    }

    h2 {
      color: #002f6c;
      font-size: 2rem;
    }

    p {
      font-size: 1.1rem;
      color: #333;
    }

    footer {
      background-color: #002f6c;
      color: white;
      text-align: center;
      padding: 30px 20px;
      font-size: 0.9rem;
    }

    /* Animations */
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes slideUp {
      from {
        transform: translateY(30px);
        opacity: 0;
      }
      to {
        transform: translateY(0);
        opacity: 1;
      }
    }

    @media (max-width: 600px) {
      .hero-text {
        font-size: 2rem;
        padding: 20px;
      }

      .cta-message {
        font-size: 1rem;
      }

      .navbar nav a {
        margin-left: 10px;
        font-size: 0.9rem;
      }
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <header class="navbar">
    <div class="logo">
      <img src="https://via.placeholder.com/30" alt="logo" />
      charity: water
    </div>
    <nav>
      <a href="#about">About</a>
      <a href="#donate">Donate</a>
      <a href="#impact">Impact</a>
    </nav>
  </header>

  <!-- Top Image -->
  <img class="top-image" src="photo water fam/water-well.jpg" alt="Community gathering at water well" />

  <!-- Hero Section -->
  <div class="hero">
    <div class="hero-text">
      Make Waves.<br />
      Fuel Change.
    </div>
  </div>

  <!-- CTA Section -->
  <div class="cta-container" id="donate">
    <div class="brand">
      <div class="brand-logo">💧</div>
      charity: water
    </div>
    <div class="cta-message">
      Join us to support clean water access. Be part of the solution!
    </div>
    <a href="https://donate.stripe.com/test" class="cta-button" target="_blank">
      $40 can give one person access to clean water
    </a>
  </div>

  <!-- About Section -->
  <section id="about">
    <h2>About Us</h2>
    <p>
      charity: water is a nonprofit organization bringing clean and safe drinking water to people in developing countries. Our mission is to end the water crisis by funding sustainable water projects.
    </p>
  </section>

  <!-- Impact Section -->
  <section id="impact">
    <h2>Our Impact</h2>
    <p>
      Since 2006, we've funded more than 111,000 water projects in 29 countries, providing over 15 million people with clean water. Every dollar you give goes directly to the field thanks to our 100% donation model.
    </p>
  </section>

  <!-- Footer -->
  <footer>
    © 2025 charity: water | Contact: hello@charitywater.org
  </footer>

</body>
</html>
