# Kburke6.github.io
Portfolio 



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>

  <style>
    :root {
      --bg: #0f0f0f;
      --card: #1a1a1a;
      --text: #f4f4f4;
      --accent: #4ea1ff;
      --accent2: #6f5bff;
    }
    * {
      margin: 0; padding: 0; box-sizing: border-box;
      font-family: "Inter", Arial, sans-serif;
    }
    body {
      background: var(--bg);
      color: var(--text);
      line-height: 1.5;
    }

    /* NAVBAR */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1.5rem 8%;
      position: fixed;
      top: 0;
      width: 100%;
      background: rgba(10,10,10,0.8);
      backdrop-filter: blur(10px);
      z-index: 1000;
    }
    nav a {
      color: var(--text);
      text-decoration: none;
      font-size: 1.1rem;
      margin-left: 2rem;
      transition: 0.3s;
    }
    nav a:hover { color: var(--accent); }

    /* HERO */
    .hero {
      height: 100vh;
      display: flex;
      align-items: center;
      padding: 0 8%;
      background: linear-gradient(120deg, #101010, #161616);
    }
    .hero h1 {
      font-size: 3.8rem;
      margin-bottom: 1rem;
    }
    .hero h1 span {
      background: linear-gradient(90deg, var(--accent), var(--accent2));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .hero p {
      max-width: 550px;
      opacity: 0.85;
      font-size: 1.15rem;
    }

    .btn {
      display: inline-block;
      margin-top: 2rem;
      padding: 0.9rem 1.7rem;
      background: var(--accent);
      color: #000;
      text-decoration: none;
      border-radius: 8px;
      font-weight: 600;
      transition: 0.3s;
    }
    .btn:hover {
      background: var(--accent2);
    }

    /* SECTIONS */
    section {
      padding: 6rem 8%;
    }
    h2 {
      font-size: 2.6rem;
      margin-bottom: 2rem;
      text-align: center;
    }

    /* PROJECTS */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
    }
    .project-card {
      background: var(--card);
      padding: 1.5rem;
      border-radius: 12px;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .project-card:hover {
      transform: translateY(-5px);
      box-shadow: 0px 10px 25px rgba(0,0,0,0.5);
    }
    .project-card h3 {
      margin-bottom: 0.5rem;
      font-size: 1.4rem;
    }
    .project-card p {
      opacity: 0.85;
      margin-bottom: 1rem;
    }
    .project-card a {
      color: var(--accent);
      text-decoration: none;
      font-weight: 600;
    }

    /* FOOTER */
    footer {
      text-align: center;
      padding: 2rem 0;
      opacity: 0.6;
    }
  </style>
</head>

<body>
  <nav>
    <div class="logo">MyPortfolio</div>
    <div>
      <a href="#projects">Projects</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <!-- HERO -->
  <section class="hero">
    <div>
      <h1>Hello, I'm <span>Keiran Burke</span></h1>
      <p>
      Hi I am an 3d computer Animation majorfrom Columbia College Chicago who has is working to learn code to help round out my crafts. Welcome to my portfolio.
      </p>
      <a href="#projects" class="btn">View Projects</a>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects">
    <h2>Featured Projects</h2>
    <div class="projects">

      <div class="project-card">
        <h3>Animation Hotspots</h3>
        <p>This project was created to have an understanding of where animation jobs are located within America today and how any are in those certain locations. It took alot of work getting the code to to what i wanted but we eventually got there.</p>
        <a href="#">file:///C:/Users/Burke003/Desktop/BurkeProject2.2/AnimationHotspots.html →</a>
      </div>

      <div class="project-card">
        <h3>Project Two</h3>
        <p>Another awesome thing you made, with a punchy description.</p>
        <a href="#">View on GitHub →</a>
      </div>

      <div class="project-card">
        <h3>Project Three</h3>
        <p>Something interesting worth showcasing in your portfolio.</p>
        <a href="#">View on GitHub →</a>
      </div>

    </div>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <h2>About Me</h2>
    <p style="max-width:700px;margin:auto;text-align:center;">
     Hi I am an 3d computer Animation majorfrom Columbia College Chicago who has is working to learn code to help round out my crafts. Welcome to my portfolio. .
    </p>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <h2>Contact</h2>
    <p style="text-align:center;">
      Feel free to reach out: Burke003@colum.edu  
      <br /><br />
      <a href="mailto:Burke003@colum.edu" class="btn">Email Me</a>
    </p>
  </section>

  <footer>
    © 2025 Keiran Burke — All Rights Reserved.
  </footer>

