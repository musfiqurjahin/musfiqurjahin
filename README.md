<!-- HTML README for GitHub Homepage -->

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Musfiqur Jahin's GitHub Profile</title>
  <style>
    body {
      font-family: 'Courier New', monospace;
      background-color: #0d0d0d;
      color: #00ff00;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    header {
      margin-top: 50px;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      letter-spacing: 2px;
      text-shadow: 0 0 10px #00ff00;
      animation: flicker 2s infinite alternate;
    }

    header h2 {
      font-size: 1.5rem;
      color: #fff;
    }

    @keyframes flicker {
      0% { opacity: 0.8; }
      100% { opacity: 1; }
    }

    .social-icons {
      margin: 30px 0;
    }

    .social-icons a {
      margin: 0 10px;
      font-size: 2rem;
      color: #00ff00;
      text-decoration: none;
      transition: transform 0.2s ease;
    }

    .social-icons a:hover {
      transform: scale(1.2);
    }

    .contribution {
      margin-top: 50px;
      background-color: #121212;
      padding: 20px;
      border-radius: 10px;
      width: 90%;
      max-width: 800px;
    }

    .contribution h3 {
      text-align: center;
      font-size: 2rem;
      margin-bottom: 20px;
    }

    .contribution pre {
      background-color: #0a0a0a;
      color: #00ff00;
      padding: 20px;
      border-radius: 10px;
      overflow-x: auto;
    }

    .skills {
      margin-top: 50px;
      padding: 20px;
      background-color: #121212;
      border-radius: 10px;
      width: 90%;
      max-width: 800px;
    }

    .skills h3 {
      font-size: 2rem;
      text-align: center;
      margin-bottom: 20px;
    }

    .skills .skill-badge {
      display: inline-block;
      margin: 5px;
      padding: 10px 20px;
      background-color: #0a0a0a;
      border: 1px solid #00ff00;
      border-radius: 20px;
      font-size: 1rem;
      color: #00ff00;
    }

    footer {
      margin-top: 50px;
      color: #999;
      text-align: center;
    }

    footer p {
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

<header>
  <h1>Musfiqur Jahin</h1>
  <h2>Passionate Programmer & GitHub Contributor</h2>

  <div class="social-icons">
    <a href="https://github.com/username" target="_blank">&#x1F517; GitHub</a>
    <a href="https://twitter.com/username" target="_blank">&#x1F517; Twitter</a>
    <a href="https://linkedin.com/in/username" target="_blank">&#x1F517; LinkedIn</a>
  </div>
</header>

<section class="contribution">
  <h3>GitHub Contribution Stats</h3>
  <pre>
    Total Contributions: 10,000+
    Active Repositories: 25
    Languages Used: JavaScript, Python, HTML/CSS, C++, Java
  </pre>
</section>

<section class="skills">
  <h3>Skills & Expertise</h3>
  <span class="skill-badge">JavaScript</span>
  <span class="skill-badge">Python</span>
  <span class="skill-badge">HTML & CSS</span>
  <span class="skill-badge">C++</span>
  <span class="skill-badge">Java</span>
  <span class="skill-badge">React.js</span>
  <span class="skill-badge">Node.js</span>
</section>

<footer>
  <p>© 2024 Musfiqur Jahin | Always coding, always learning &#x1F9D1;&#x200D;&#x1F4BB;</p>
</footer>

</body>
</html>

