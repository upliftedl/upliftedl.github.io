<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>upliftedl | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background-color: #f5f5f5;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #1e1e2f;
      color: white;
      padding: 2rem;
      text-align: center;
    }

    header h1 {
      margin-bottom: 0.5rem;
      font-size: 2.5rem;
    }

    nav a {
      margin: 0 1rem;
      color: #fff;
      text-decoration: none;
      font-weight: 600;
    }

    .container {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 1rem;
    }

    section {
      margin-bottom: 2rem;
    }

    h2 {
      color: #1e1e2f;
      margin-bottom: 1rem;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #1e1e2f;
      color: white;
      margin-top: 2rem;
    }

    .project {
      background: white;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      margin-bottom: 1rem;
    }

    a.button {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.5rem 1rem;
      background: #1e1e2f;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }

    a.button:hover {
      background: #33334d;
    }
  </style>
</head>
<body>
  <header>
    <h1>upliftedl</h1>
    <p>Developer | Designer | Learner</p>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="container">
    <section id="about">
      <h2>About Me</h2>
      <p>Hey! I'm upliftedl, a passionate developer exploring the world of web and software development. I love building things that are useful, clean, and creative. This is my digital space to share what I build and learn.</p>
    </section>

    <section id="projects">
      <h2>Projects</h2>

      <div class="project">
        <h3>My Portfolio Website</h3>
        <p>A responsive and minimal personal website built with HTML, CSS, and some love.</p>
        <a class="button" href="#">View Project</a>
      </div>

      <div class="project">
        <h3>Ride Sharing App (WIP)</h3>
        <p>A Flutter + Firebase powered platform for smart, secure, real-time ride matching and payments.</p>
        <a class="button" href="#">Coming Soon</a>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <p>Feel free to reach out for collaborations or just a chat.</p>
      <p>Email: yourname@example.com</p>
      <p>GitHub: <a href="https://github.com/upliftedl" target="_blank">upliftedl</a></p>
    </section>
  </div>

  <footer>
    <p>© 2025 upliftedl. All rights reserved.</p>
  </footer>
</body>
</html>
