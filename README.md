<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Responsive Web Page</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header>
    <nav>
      <ul class="navbar">
        <li><a href="#">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h1>Welcome to Our Website</h1>
    <p>Your journey begins here.</p>
    <button>Get Started</button>
  </section>

  <section id="about">
    <h2>Introduction</h2>
    <p>This website is built to demonstrate a responsive design using HTML and CSS.</p>
  </section>

  <section id="services">
    <h2>Services</h2>
    <ul>
      <li>Web Design</li>
      <li>Development</li>
      <li>SEO Optimization</li>
    </ul>
  </section>

  <section id="testimonials">
    <h2>Testimonials</h2>
    <p>"Great service and responsive design!" - Client A</p>
    <p>"Highly recommend working with them." - Client B</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="message">Message:</label>
      <textarea id="message" name="message" required></textarea>

      <button type="submit">Submit</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Responsive Web. All rights reserved.</p>
  </footer>

</body>
</html>
