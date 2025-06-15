---
layout: none
---

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chris Green</title>
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    :root {
      --blue: #183153;
      --white: #ffffff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Open Sans', sans-serif;
      background-color: var(--white);
      color: var(--blue);
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

a, h1, h2, h3, h4, h5, h6, p, div {
  color: var(--blue);
}

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
      border-bottom: 1px solid #ccc;
    }

    .home-logo {
      height: 40px;
    }

    .name {
      font-size: 1.5rem;
      font-weight: bold;
      color: var(--blue);
    }

    .layout {
      display: flex;
      flex: 1;
    }

    nav {
      width: 200px;
      padding: 2rem;
      border-right: 1px solid #ccc;
    }

    nav a {
      display: block;
      margin-bottom: 1rem;
      text-decoration: none;
      color: var(--blue);
      font-weight: 600;
    }

    main {
      flex: 1;
      padding: 2rem;
    }

    .socials {
      display: flex;
      gap: 1rem;
      padding: 2rem;
      justify-content: flex-end;
    }

    .socials a {
      color: var(--blue);
      font-size: 1.5rem;
      text-decoration: none;
    }

    @media (max-width: 768px) {
      .layout {
        flex-direction: column;
      }

      nav {
        width: 100%;
        border-right: none;
        border-bottom: 1px solid #ccc;
        display: flex;
        justify-content: space-around;
      }

      .socials {
        justify-content: center;
        padding: 1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="left-header">
    <a href="/">
      <img src="/assets/logo.png" alt="Home Logo" class="home-logo">
    </a>
    <div class="name">Chris Green</div>
    </div>  
  </header>

  <div class="layout">
    <nav>
      <a href="/resume">Resume</a>
      <a href="/cv">CV</a>
      <a href="/speaking">Speaking</a>
      <a href="/projects">Projects</a>
    </nav>

    <main>
      <p>Welcome to my site. Please explore the links to learn more about my work.</p>
    </main>
  </div>

  <div class="socials">
    <a href="https://linkedin.com/in/yourprofile" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
    <a href="https://github.com/yourprofile" target="_blank" title="GitHub"><i class="fab fa-github"></i></a>
    <a href="https://twitter.com/yourprofile" target="_blank" title="Twitter"><i class="fab fa-twitter"></i></a>
    <a href="https://bsky.app/profile/yourprofile" target="_blank" title="Bluesky"><i class="fas fa-cloud"></i></a>
    <a href="https://mastodon.social/@yourprofile" target="_blank" title="Mastodon"><i class="fab fa-mastodon"></i></a>
  </div>
</body>
</html>
