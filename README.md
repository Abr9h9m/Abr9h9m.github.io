<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Abraham Ashade | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* General Styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #0d0d0d;
      color: #e0e0e0;
      line-height: 1.6;
      scroll-behavior: smooth;
    }
    a {
      color: #1e90ff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    section {
      max-width: 900px;
      margin: 2rem auto;
      padding: 2rem;
      background-color: #1b1b1b;
      border-radius: 15px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.7);
    }
    h1, h2 {
      color: #ffffff;
    }
    h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
      text-shadow: 0 0 5px #1e90ff, 0 0 10px #1e90ff, 0 0 20px #1e90ff;
      animation: glow 2s ease-in-out infinite alternate;
    }
    @keyframes glow {
      from { text-shadow: 0 0 5px #1e90ff, 0 0 10px #1e90ff, 0 0 20px #1e90ff; }
      to { text-shadow: 0 0 10px #00ffff, 0 0 20px #00ffff, 0 0 30px #00ffff; }
    }
    h2 {
      margin-bottom: 1rem;
      border-bottom: 2px solid #1e90ff;
      padding-bottom: 0.3rem;
    }
    ul {
      list-style: none;
      padding-left: 0;
    }
    ul li {
      margin-bottom: 0.5rem;
    }

    /* Header */
    header {
      text-align: center;
      padding: 3rem 1rem;
      background-color: #0a0a0a;
      position: relative;
    }
    .profile-pic {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      border: 4px solid #1e90ff;
      margin: 0 auto 1rem;
      object-fit: cover;
      transition: transform 0.3s;
    }
    .profile-pic:hover {
      transform: scale(1.1) rotate(5deg);
      box-shadow: 0 0 20px #1e90ff;
    }
    header p {
      font-size: 1.2rem;
      color: #a0a0a0;
    }

    /* Projects Cards */
    .project-card {
      background-color: #2a2a2a;
      border-radius: 10px;
      padding: 1rem;
      margin-bottom: 1rem;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .project-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 20px rgba(30, 144, 255, 0.5);
    }

    /* GitHub Stats */
    .stats img {
      max-width: 100%;
      margin: 1rem 0;
      border-radius: 10px;
    }

    /* Buttons */
    .social-buttons {
      margin-top: 1rem;
    }
    .social-buttons a {
      display: inline-block;
      margin: 0 10px;
      padding: 10px 20px;
      border: 2px solid #1e90ff;
      border-radius: 30px;
      color: #1e90ff;
      font-weight: bold;
      transition: all 0.3s;
    }
    .social-buttons a:hover {
      background-color: #1e90ff;
      color: #0d0d0d;
      box-shadow: 0 0 15px #1e90ff;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #0a0a0a;
      color: #888;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

<header>
  <!-- Replace src="profile.jpg" with your actual photo path -->
  <img src="profile.jpg" alt="Abraham Ashade" class="profile-pic">
  <h1>👋 Hi, I'm Abraham Ashade</h1>
  <p>Computer Science Major | Data Science Concentration | Cybersecurity Enthusiast</p>
  <div class="social-buttons">
    <a href="https://github.com/USERNAME" target="_blank">GitHub</a>
    <a href="https://www.linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
    <a href="mailto:youremail@example.com">Email</a>
  </div>
</header>

<section>
  <h2>🚀 About Me</h2>
  <p>
    I’m a second-year <strong>Computer Science student</strong> passionate about building tools, solving problems, and creating systems that deliver real value. I enjoy translating complex requirements into <strong>clean, scalable, and efficient code</strong>.
  </p>
  <ul>
    <li>🎓 Sophomore at Elizabeth City State University</li>
    <li>💻 Interests: software development, data science, cybersecurity</li>
    <li>⚡ Quick learner with sharp attention to detail</li>
    <li>🤝 Experienced working with teams via Peer Forward, ROTC, SGA, and group projects</li>
    <li>🧠 Passionate about applying technology to solve real-world problems</li>
  </ul>
</section>

<section>
  <h2>🛠️ Tech Stack</h2>
  <p><strong>Languages:</strong> Python, Java, C++, HTML, CSS, JavaScript</p>
  <p><strong>Tools & Technologies:</strong> Git, GitHub, Linux, Bash, SQL, VS Code, Figma</p>
  <p><strong>Interests:</strong> Machine Learning, Data Visualization, Cybersecurity, Mobile App Development</p>
</section>

<section>
  <h2>📚 Highlighted Projects</h2>
  <div class="project-card">
    <strong>Mobile App Development Group Project</strong>
    <p>Collaborative project designing, coding, and testing a fully functional mobile application with focus on system requirements and user experience.</p>
  </div>
  <div class="project-card">
    <strong>Information Systems Course Projects</strong>
    <p>Hands-on systems development and analysis, including networking, enterprise systems, decision support, and business IT design.</p>
  </div>
</section>

<section class="stats">
  <h2>📊 GitHub Stats</h2>
  <p>Replace <code>USERNAME</code> with your GitHub username</p>
  <img src="https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=tokyonight" alt="GitHub Stats">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&theme=tokyonight" alt="Top Languages">
</section>

<section>
  <h2>🌱 Currently Learning</h2>
  <ul>
    <li>Advanced data structures</li>
    <li>Data science workflows</li>
    <li>Secure coding practices</li>
    <li>Cloud technologies</li>
  </ul>
</section>

<footer>
  &copy; 2025 Abraham Ashade. All rights reserved.
</footer>

</body>
</html>
