<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<title>Pritam Maharjan | Portfolio</title>

<style>
  body {
    margin: 0;
    font-family: "Fira Code", monospace, Consolas, monospace;
    background: #0f0f10;
    color: #e1e1e1;
    line-height: 1.6;
  }

  header {
    background: #111;
    padding: 60px 20px;
    text-align: center;
  }

  header h1 {
    font-size: 2.5rem;
    color: #00ff7f;
    margin: 0;
  }

  header p {
    font-size: 1.1rem;
    margin-top: 8px;
    color: #82aaff;
  }

  main {
    max-width: 900px;
    margin: auto;
    padding: 30px 20px;
  }

  .section {
    margin-bottom: 40px;
  }

  .section h2 {
    font-size: 1.8rem;
    color: #00ffc8;
    border-bottom: 2px solid #00ffc8;
    padding-bottom: 6px;
  }

  .skills-list,
  .experience-list {
    list-style: none;
    padding: 0;
  }

  .skills-list li,
  .experience-list li {
    margin-bottom: 8px;
    padding-left: 12px;
    position: relative;
  }

  .skills-list li::before,
  .experience-list li::before {
    content: "•";
    position: absolute;
    left: 0;
    color: #00ff7f;
  }

  .contact a {
    color: #82aaff;
    text-decoration: none;
    font-weight: bold;
  }
</style>
</head>
<body>

<header>
  <h1>Pritam Maharjan</h1>
  <p>Software Engineer | Web Developer | Always Learning</p>
</header>

<main>

  <div class="section about">
    <h2>About Me</h2>
    <p>Hello! I’m a passionate web developer focused on building clean, predictable, human-centered web experiences. I create interfaces that feel simple and behave consistently — with code that explains itself.</p>
  </div>

  <div class="section skills">
    <h2>Skills</h2>
    <ul class="skills-list">
      <li>Frontend Development (React, Tailwind CSS)</li>
      <li>UI Logic & Component Thinking</li>
      <li>Backend APIs & Performance Debugging</li>
      <li>Version Control with Git</li>
      <li>Problem-Solving Mindset</li>
    </ul>
  </div>

  <div class="section experience">
    <h2>Experience</h2>
    <ul class="experience-list">
      <li>Junior .NET Developer – Cypha Interactive</li>
      <li>Software Engineer – GO Tech International</li>
      <li>Developer Intern – PIEX Education</li>
    </ul>
  </div>

  <div class="section contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:primgdev@gmail.com">primgdev@gmail.com</a></p>
    <p>Location: Sydney, Australia</p>
  </div>

</main>

</body>
</html>
