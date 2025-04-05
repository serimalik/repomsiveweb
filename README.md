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

/* General Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  padding: 1em 0;
}

.navbar {
  list-style: none;
  display: flex;
  justify-content: center;
  margin: 0;
  padding: 0;
}

.navbar li {
  margin: 0 15px;
}

.navbar a {
  color: white;
  text-decoration: none;
}

.hero {
  text-align: center;
  padding: 50px 20px;
  background: #f4f4f4;
}

.hero button {
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
}

section {
  padding: 40px 20px;
}

form {
  max-width: 500px;
  margin: auto;
  display: flex;
  flex-direction: column;
}

form label, form input, form textarea {
  margin-bottom: 15px;
}

button[type="submit"] {
  padding: 10px;
  font-size: 16px;
}

footer {
  text-align: center;
  background: #333;
  color: white;
  padding: 20px;
}

/* Media Queries for Responsiveness */
@media (max-width: 768px) {
  .navbar {
    flex-direction: column;
    align-items: center;
  }

  .hero h1 {
    font-size: 24px;
  }
}

@media (max-width: 480px) {
  .hero button {
    width: 100%;
  }
}
