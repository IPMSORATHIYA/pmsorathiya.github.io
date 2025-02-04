<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="PMSorathiya">
  <title>Photography Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="navbar">
      <div class="logo">
        <h1>PhotoVista</h1>
      </div>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#portfolio">Portfolio</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="home" class="hero-section">
    <div class="hero-text">
      <h2>Capturing the Moment</h2>
      <p>Explore my world through the lens of photography.</p>
    </div>
  </section>

  <section id="portfolio" class="portfolio-section">
    <h2>Portfolio</h2>
    <div class="gallery">
      <div class="image-card">
        <img src="https://via.placeholder.com/300" alt="Nature">
        <p>Nature Photography</p>
      </div>
      <div class="image-card">
        <img src="https://via.placeholder.com/300" alt="Landscape">
        <p>Landscape Photography</p>
      </div>
      <div class="image-card">
        <img src="https://via.placeholder.com/300" alt="Cityscape">
        <p>Cityscape Photography</p>
      </div>
    </div>
  </section>

  <section id="about" class="about-section">
    <h2>About Me</h2>
    <p>Hello! I'm a passionate photographer who loves capturing beautiful moments and stories through my lens. With years of experience, I aim to provide high-quality, memorable images.</p>
  </section>

  <section id="contact" class="contact-section">
    <h2>Contact</h2>
    <form action="submit_form.php" method="POST">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 PhotoVista. All rights reserved.</p>
  </footer>
</body>
</html>
