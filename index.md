<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>wretiii.com</title>
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --blue-dark: #2A495E;
      --blue-mid: #3E657A;
      --blue-light: #5E95AE;
      --text-color: #ffffff;
      --highlight: #A0C3D2;
      --bg: #f9f9f9;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Open Sans', sans-serif;
      background-color: var(--bg);
      color: #333;
    }

    header {
      background-color: var(--blue-dark);
      color: var(--text-color);
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      display: flex;
      align-items: center;
    }

    .logo img {
      height: 40px;
      margin-right: 10px;
    }

    .logo span {
      font-size: 1.5rem;
      font-weight: bold;
    }

    nav {
      display: flex;
      gap: 2rem;
    }

    nav a {
      color: var(--text-color);
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }

    nav a:hover {
      color: var(--highlight);
    }

    .hero {
      background: linear-gradient(to right, var(--blue-mid), var(--blue-light));
      color: white;
      padding: 4rem 2rem;
      text-align: center;
      border-bottom-left-radius: 50% 10%;
      border-bottom-right-radius: 50% 10%;
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.2rem;
    }

    .features {
      display: flex;
      justify-content: space-around;
      background-color: white;
      padding: 3rem 2rem;
    }

    .feature-box {
      background-color: var(--blue-dark);
      color: white;
      padding: 2rem;
      border-radius: 12px;
      width: 30%;
      text-align: center;
    }

    .feature-box h2 {
      border-bottom: 2px solid white;
      padding-bottom: 0.5rem;
      margin-bottom: 1rem;
    }

    footer {
      background-color: var(--blue-dark);
      color: white;
      padding: 2rem;
      text-align: center;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <img src="/assets/logo.png" alt="wretiii.com logo">
      <span>wretiii.com</span>
    </div>
    <nav>
      <a href="/">Home</a>
      <a href="/resume">Resume</a>
      <a href="/cv">CV</a>
      <a href="/speaking">Speaking</a>
      <a href="/projects">Projects</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Discover the power of people, business and technology.</h1>
    <p>wretiii.com bridges the gap between ideas and execution in security and consulting.</p>
  </section>

  <section class="features">
    <div class="feature-box">
      <h2>Security</h2>
      <p>Deep expertise in penetration testing, assessments, and risk frameworks.</p>
    </div>
    <div class="feature-box">
      <h2>Cloud</h2>
      <p>Architecting compliant cloud infrastructure aligned to business goals.</p>
    </div>
    <div class="feature-box">
      <h2>Digital Infrastructure</h2>
      <p>Guiding resilient IT systems that adapt to evolving security threats.</p>
    </div>
  </section>

  <footer>
    &copy; 2025 wretiii.com — Built with ❤️ on GitHub Pages
  </footer>
</body>
</html>
