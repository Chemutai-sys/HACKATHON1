<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <!--2,internal css-->
  <style>
    p{
      colour:brown;
      font-size:20px;
    }
  </style>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <nav>
      <h1>My Portfolio</h1>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I'm an aspiring web developer passionate about building impactful web experiences, finding problems and the solutions to curb it </p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <p>Basic calculator</p>
    <div class="project-list">
      <!-- Projects will be dynamically injected from the database -->
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form id="contact-form">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 My Portfolio. All rights reserved.</p>
  </footer>

  <script src="app.js"></script>
</body>
</html>
# HACKATHON1
