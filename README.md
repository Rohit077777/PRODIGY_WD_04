<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Rohit Ishwar Chaudhari - Web Developer Portfolio</title>
  <style>
    /* General Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
      color: #333;
    }

    a {
      text-decoration: none;
      color: #333;
    }

    h1, h2, h3 {
      color: #444;
      margin: 20px 0;
    }

    /* Navbar */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px;
      background-color: #333;
      color: white;
    }

    .navbar ul {
      display: flex;
      list-style: none;
      gap: 20px;
    }

    .navbar a {
      color: white;
      transition: color 0.3s ease;
    }

    .navbar a:hover {
      color: #bbb;
    }

    /* Hero Section */
    .hero {
      background-image: url('https://via.placeholder.com/1200x600');
      height: 600px;
      background-size: cover;
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      text-align: center;
    }

    .hero h1 {
      font-size: 56px;
    }

    .hero h2 {
      font-size: 24px;
      margin: 10px 0;
    }

    /* About Section */
    .about {
      padding: 60px;
      text-align: center;
      background-color: white;
    }

    .about img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      margin-bottom: 20px;
    }

    /* Skills Section */
    .skills {
      padding: 60px;
      background-color: #f9f9f9;
    }

    .skills h2 {
      text-align: center;
    }

    .skills-container {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      margin-top: 40px;
    }

    .skill {
      width: 250px;
      text-align: center;
      background-color: white;
      padding: 20px;
      margin: 10px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s;
    }

    .skill:hover {
      transform: translateY(-5px);
    }

    /* Projects Section */
    .projects {
      padding: 60px;
      background-color: white;
    }

    .projects h2 {
      text-align: center;
    }

    .projects-container {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      margin-top: 40px;
    }

    .project-card {
      width: 300px;
      background-color: white;
      padding: 20px;
      margin: 10px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    .project-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 5px;
    }

    .project-card h3 {
      margin: 15px 0;
    }

    /* Footer */
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 30px 0;
    }

    footer p {
      margin: 0;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <header>
    <div class="navbar">
      <div class="logo">
        <h1>Rohit Chaudhari</h1>
      </div>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
      <h1>Hi, I'm Rohit Ishwar Chaudhari</h1>
      <h2>Web Developer | Software Engineer</h2>
    </div>
  </section>

  <!-- About Section -->
  <section class="about" id="about">
    <h2>About Me</h2>
    <img src="https://via.placeholder.com/150" alt="Rohit Chaudhari">
    <p>Hello! I'm Rohit, a passionate web developer and software engineer based in Maharashtra, India. I have a strong foundation in front-end and back-end development, and I love building dynamic and interactive web applications.</p>
    <p>With a background in computer science and engineering, I have experience working on a variety of projects, including web development, AI, and blockchain-based solutions.</p>
  </section>

  <!-- Skills Section -->
  <section class="skills" id="skills">
    <h2>Skills</h2>
    <div class="skills-container">
      <div class="skill">
        <h3>HTML & CSS</h3>
        <p>Expertise in building responsive and visually appealing websites using HTML5, CSS3, and modern frameworks like Bootstrap.</p>
      </div>
      <div class="skill">
        <h3>JavaScript</h3>
        <p>Proficient in JavaScript (ES6+), with experience in front-end frameworks like React and back-end frameworks like Node.js.</p>
      </div>
      <div class="skill">
        <h3>Python</h3>
        <p>Experienced in Python for data analysis, automation, and AI-driven projects.</p>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section class="projects" id="projects">
    <h2>Projects</h2>
    <div class="projects-container">
      <div class="project-card">
        <img src="https://via.placeholder.com/300x200" alt="Project 1">
        <h3>Blockchain Voting System</h3>
        <p>Developed a secure and transparent voting system using blockchain technology to ensure election integrity.</p>
      </div>
      <div class="project-card">
        <img src="https://via.placeholder.com/300x200" alt="Project 2">
        <h3>AI-Based Learning Path Generator</h3>
        <p>Built an AI-powered platform that generates personalized learning paths for students based on their progress and interests.</p>
      </div>
      <div class="project-card">
        <img src="https://via.placeholder.com/300x200" alt="Project 3">
        <h3>Smart Financial Wellness Platform</h3>
        <p>Designed a platform that helps users manage their finances by analyzing spending patterns and offering saving tips.</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer id="contact">
    <p>&copy; 2024 Rohit Ishwar Chaudhari | Web Developer | <a href="mailto:rohit@example.com">Contact Me</a></p>
  </footer>

</body>
</html>
