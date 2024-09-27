<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <ul>
        <li><a href="#about">About Me</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm a web developer with a passion for creating dynamic and responsive websites.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Project 1</h3>
      <p>Details about Project 1.</p>
    </div>
    <div class="project">
      <h3>Project 2</h3>
      <p>Details about Project 2.</p>
    </div>
    <div class="project">
      <h3>Project 3</h3>
      <p>Details about Project 3.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <form id="contact-form">
      <label for="name">Name:</label>
      <input type="text" id="name" required>
      <label for="email">Email:</label>
      <input type="email" id="email" required>
      <label for="message">Message:</label>
      <textarea id="message" required></textarea>
      <button type="submit">Submit</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2024 My Portfolio</p>
  </footer>

  <script src="scripts.js"></script>
</body>
</html>
