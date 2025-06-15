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
      --accent: #1F1F1F;
      --link: #9C9CFF;
    }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: var(--bg);
      color: var(--text);
      display: flex;
      flex-direction: column;
      height: 100vh;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: var(--accent);
      padding: 10px 20px;
    }
    .logo {
      display: flex;
      align-items: center;
    }
    .logo img {
      height: 40px;
      margin-right: 10px;
      cursor: pointer;
    }
    nav.left-menu {
      width: 200px;
      background-color: var(--accent);
      padding: 20px;
      min-height: 100vh;
      box-sizing: border-box;
    }
    nav.left-menu ul {
      list-style: none;
      padding: 0;
    }
    nav.left-menu li {
      margin: 15px 0;
    }
    nav.left-menu a {
      color: var(--link);
      text-decoration: none;
    }
    .social-icons img {
      height: 24px;
      margin-left: 10px;
      filter: brightness(0) invert(1);
      cursor: pointer;
    }
    .main-content {
      flex: 1;
      display: flex;
    }
    .page-content {
      flex: 1;
      padding: 40px;
    }
  </style>
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
