<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Personal webpage for showcasing my work and skills.">
  <title>Personal Website</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <!-- Header -->
  <header>
    <div class="container">
      <h1>Aditya Gupta</h1>
      <p>Student</p>
    </div>
  </header>

  <!-- Navigation Bar -->
  <nav>
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#portfolio">Portfolio</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- About Section -->
  <section id="about">
    <div class="container">
      <h2>About Me</h2>
      <p> Hi, I am currently studying in class 9.</p>
    </div>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio">
    <div class="container">
      <h2>Portfolio</h2>
      <div class="portfolio-grid">
        <div class="portfolio-item">
          <img src="https://via.placeholder.com/300" alt="Project 1">
          <p>Project 1 Description</p>
        </div>
        <div class="portfolio-item">
          <img src="https://via.placeholder.com/300" alt="Project 2">
          <p>Project 2 Description</p>
        </div>
        <div class="portfolio-item">
          <img src="https://via.placeholder.com/300" alt="Project 3">
          <p>Project 3 Description</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <div class="container">
      <h2>Contact Me</h2>
      <form action="#" method="post">
        <label for="name">Your Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Your Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Your Message:</label>
        <textarea id="message" name="message" required></textarea>

        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2024 Aditya Gupta. All rights reserved.</p>
    </div>
  </footer>

</body>
</html>
