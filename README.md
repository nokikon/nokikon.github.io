<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Your Name</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(135deg, #667eea, #764ba2);
      color: #fff;
      min-height: 100vh;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 60px 20px;
    }

    header {
      text-align: center;
      margin-bottom: 80px;
    }

    header h1 {
      font-size: 3rem;
      font-weight: 700;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    section {
      background: rgba(255, 255, 255, 0.1);
      border-radius: 16px;
      padding: 40px;
      margin-bottom: 40px;
      backdrop-filter: blur(10px);
    }

    h2 {
      font-size: 1.8rem;
      margin-bottom: 20px;
    }

    p {
      line-height: 1.7;
      opacity: 0.95;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: rgba(0, 0, 0, 0.2);
      padding: 25px;
      border-radius: 12px;
      transition: transform 0.2s ease, background 0.2s ease;
    }

    .card:hover {
      transform: translateY(-5px);
      background: rgba(0, 0, 0, 0.35);
    }

    .card h3 {
      margin-bottom: 10px;
    }

    footer {
      text-align: center;
      opacity: 0.8;
      margin-top: 60px;
      font-size: 0.9rem;
    }

    a {
      color: #ffd86b;
      text-decoration: none;
      font-weight: 600;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <div class="container">
    <header>
      <h1>Your Name</h1>
      <p>Developer • Designer • Builder</p>
    </header>

    <section>
      <h2>About Me</h2>
      <p>
        Hey! I’m building things on the web and learning as I go.
        This website is hosted for free using GitHub Pages 🚀
      </p>
    </section>

    <section>
      <h2>Projects</h2>
      <div class="projects">
        <div class="card">
          <h3>Project One</h3>
          <p>A short description of what this project does.</p>
        </div>
        <div class="card">
          <h3>Project Two</h3>
          <p>Another cool thing you built or are working on.</p>
        </div>
        <div class="card">
          <h3>Project Three</h3>
          <p>Ideas count too — not everything has to be finished.</p>
        </div>
      </div>
    </section>

    <section>
      <h2>Contact</h2>
      <p>
        Find me on
        <a href="https://github.com/yourusername" target="_blank">GitHub</a>
        or email me at
        <a href="mailto:you@example.com">you@example.com</a>
      </p>
    </section>

    <footer>
      © 2026 Your Name
    </footer>
  </div>

</body>
</html>
