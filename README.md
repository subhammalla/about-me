
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Subham | Portfolio</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9fafb;
      color: #333;
    }
    header {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 50px 20px;
    }
    header h1 {
      margin: 0;
      font-size: 3rem;
    }
    header p {
      margin: 10px 0;
      font-size: 1.2rem;
    }
    img.profile {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      margin-top: 20px;
    }
    section {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }
    h2 {
      border-bottom: 2px solid #444;
      padding-bottom: 5px;
      margin-bottom: 20px;
    }
    p {
      line-height: 1.6;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .project-card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      padding: 20px;
      transition: transform 0.2s ease;
    }
    .project-card:hover {
      transform: translateY(-5px);
    }
    .project-card h3 {
      margin-top: 0;
    }
    a {
      color: #007BFF;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .social-links a {
      display: inline-block;
      margin-right: 10px;
      margin-bottom: 5px;
    }
  </style>
</head>
<body>

<header>
  <h1>Subham</h1>
  <p>Developer | Designer | Tech Enthusiast</p>
  <img src="https://via.placeholder.com/150" alt="Profile Image" class="profile">
</header>

<section>
  <h2>About Me</h2>
  <p>Hello! I'm Subham. I enjoy creating clean, responsive, and modern websites and apps. I love learning new tech and bringing ideas to life with code and design.</p>
</section>

<section>
  <h2>School</h2>
  <p>I am currently studying at XYZ Secondary School, with a focus on science and technology subjects.</p>
</section>

<section>
  <h2>Achievements</h2>
  <ul>
    <li>Top 10 finalist in National Coding Challenge 2024</li>
    <li>Created and launched 3+ apps on Play Store</li>
    <li>Maintained open-source contributions on GitHub</li>
  </ul>
</section>

<section>
  <h2>Projects</h2>
  <div class="projects">
    <div class="project-card">
      <h3>Wallpaper App</h3>
      <p>A clean and vibrant wallpaper app inspired by Prism.</p>
      <a href="#">View Project</a>
    </div>
    <div class="project-card">
      <h3>Task Manager</h3>
      <p>Organize daily tasks with priority and reminders.</p>
      <a href="#">View Project</a>
    </div>
    <div class="project-card">
      <h3>Portfolio Site</h3>
      <p>Personal website showcasing projects and skills.</p>
      <a href="#">View Project</a>
    </div>
  </div>
</section>

<section>
  <h2>Contact</h2>
  <p>Email: <a href="mailto:subham@example.com">subham@example.com</a></p>
  <div class="social-links">
    <a href="https://facebook.com/" target="_blank">Facebook</a>
    <a href="https://instagram.com/" target="_blank">Instagram</a>
    <a href="https://youtube.com/" target="_blank">YouTube</a>
  </div>
</section>

</body>
</html>
