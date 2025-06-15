<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>wretiii.com</title>
  <style>
    :root {
      --bg: #0A0A0A;
      --text: #FFFFFF;
      --accent: #1C1C1C;
      --highlight: #2F2F2F;
      --link: #A0A0FF;
      --border: #2A2A2A;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: var(--bg);
      color: var(--text);
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: var(--accent);
      padding: 20px 40px;
      border-bottom: 1px solid var(--border);
    }

    .logo {
      display: flex;
      align-items: center;
      cursor: pointer;
    }

    .logo img {
      height: 36px;
      margin-right: 12px;
    }

    .logo span {
      font-size: 18px;
      font-weight: 600;
      color: var(--text);
    }

    .social-icons a img {
      height: 22px;
      margin-left: 15px;
      filter: brightness(0) invert(1);
      opacity: 0.7;
      transition: opacity 0.2s ease;
    }

    .social-icons a img:hover {
      opacity: 1;
    }

    .main-content {
      display: flex;
      flex: 1;
    }

    nav.left-menu {
      width: 240px;
      background-color: var(--accent);
      padding: 30px 20px;
      border-right: 1px solid var(--border);
    }

    nav.left-menu ul {
      list-style: none;
      padding: 0;
      margin: 0;
    }

    nav.left-menu li {
      margin-bottom: 20px;
    }

    nav.left-menu a {
      color: var(--text);
      text-decoration: none;
      font-weight: 500;
      transition: color 0.2s ease;
    }

    nav.left-menu a:hover {
      color: var(--link);
    }

    .page-content {
      flex: 1;
      padding: 40px 60px;
      background-color: var(--bg);
    }

    h1 {
      font-size: 32px;
      font-weight: 700;
      margin-bottom: 20px;
    }

    p {
      font-size: 16px;
      line-height: 1.6;
      color: #CCC;
    }
  </style>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <div class="logo" onclick="location.href='/'">
      <img src="/assets/logo.png" alt="Home">
      <span>wretiii.com</span>
    </div>
    <div class="social-icons">
      <a href="https://linkedin.com/in/YOURUSERNAME" target="_blank"><img src="/assets/icons/linkedin.svg" alt="LinkedIn"></a>
      <a href="https://github.com/YOURUSERNAME" target="_blank"><img src="/assets/icons/github.svg" alt="GitHub"></a>
      <a href="https://bsky.app/profile/YOURUSERNAME" target="_blank"><img src="/assets/icons/bluesky.svg" alt="Bluesky"></a>
      <a href="https://mastodon.social/@YOURUSERNAME" target="_blank"><img src="/assets/icons/mastodon.svg" alt="Mastodon"></a>
      <a href="https://x.com/YOURUSERNAME" target="_blank"><img src="/assets/icons/x.svg" alt="X"></a>
    </div>
  </header>
  <div class="main-content">
    <nav class="left-menu">
      <ul>
        <li><a href="/resume/">Resume</a></li>
        <li><a href="/cv/">CV</a></li>
        <li><a href="/speaking/">Speaking</a></li>
        <li><a href="/projects/">Projects</a></li>
      </ul>
    </nav>
    <div class="page-content">
      <h1>Welcome to wretiii.com</h1>
      <p>This is your professional site. Customize it as needed.</p>
    </div>
  </div>
</body>
</html>
