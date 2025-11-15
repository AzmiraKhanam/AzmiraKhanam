<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Azmira Khanam | Portfolio</title>  <style>
    body {
      font-family: "Poppins", sans-serif;
      margin: 0;
      padding: 0;
      background: #f0f4ff;
      color: #222;
    }

    /* NAVBAR */
    .navbar {
      background: #0055b3;
      padding: 12px 20px;
      display: flex;
      justify-content: center;
      gap: 30px;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    .navbar a {
      color: white;
      text-decoration: none;
      font-weight: 600;
      font-size: 16px;
    }

    /* HERO */
    .hero {
      background: linear-gradient(#0073e6, #0055b3);
      color: white;
      padding: 70px 20px 110px;
      text-align: center;
    }
    .hero h1 {
      font-size: 42px;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 18px;
      max-width: 800px;
      margin: auto;
      opacity: 0.9;
    }

    /* PROFILE PIC */
    .profile-pic {
      display: flex;
      justify-content: center;
      margin-top: -80px;
    }
    .profile-pic img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      border: 6px solid white;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    }

    /* MAIN LAYOUT */
    .layout {
      max-width: 1150px;
      margin: 30px auto;
      display: grid;
      grid-template-columns: 3fr 1fr;
      gap: 25px;
      padding: 0 20px;
    }

    /* LEFT CONTENT */
    section {
      background: white;
      padding: 25px;
      margin-bottom: 25px;
      border-radius: 15px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    }
    h2 {
      color: #0055b3;
      margin-bottom: 15px;
      font-size: 24px;
      text-align: left;
    }

    /* PROJECT CARDS */
    .projects-grid {
      display: grid;
      grid-template-columns: 1fr;
      gap: 18px;
    }
    .project-card {
      background: #f8fbff;
      border-left: 5px solid #0055b3;
      padding: 18px;
      border-radius: 12px;
      transition: 0.2s;
    }
    .project-card:hover {
      transform: translateY(-4px);
    }
    .project-btn {
      display: inline-block;
      margin-top: 10px;
      padding: 8px 16px;
      background: #0055b3;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-size: 14px;
    }

    /* RIGHT SIDEBAR */
    .sidebar-box {
      background: white;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      margin-bottom: 20px;
    }
    .sidebar-box h3 {
      margin-top: 0;
      color: #0055b3;
    }

    footer {
      background: #0055b3;
      color: white;
      text-align: center;
      padding: 25px 10px;
      margin-top: 40px;
    }

    @media(max-width: 900px) {
      .layout {
        grid-template-columns: 1fr;
      }
    }
  </style></head><body>  <!-- NAVBAR -->  <div class="navbar">
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </div>  <!-- HERO -->  <div class="hero">
    <h1>Azmira Khanam</h1>
    <p>Computer Engineering Student | Educator | Ex–Deputy Chief (Training), Red Crescent Youth CTG</p>
  </div>  <!-- PROFILE PICTURE -->  <div class="profile-pic">
    <img src="https://raw.githubusercontent.com/AzmiraKhanam/AzmiraKhanam/refs/heads/main/formal%20photo.jpg" alt="Azmira Khanam">
  </div>  <!-- MAIN CONTENT -->  <div class="layout"><!-- LEFT SIDE CONTENT -->
<div>
  <section id="about">
    <h2>About Me</h2>
    <p>
      Hi! I’m <strong>Azmira Khanam</strong> — a final-year B.Sc. Engineering student passionate about technology, education, and leadership.
      I previously served as the <strong>Deputy Chief (Training Department)</strong> at Red Crescent Youth, Chittagong.
      My goal is to blend engineering knowledge with teaching to create digital learning content that helps students learn easily.
    </p>
  </section>

  <!-- QUICK BIO SECTION -->
  <section id="quickbio">
    <h2>Quick Bio</h2>
    <p>I’m Azmira Khanam — a passionate learner, educator, and tech enthusiast. I love creating simple content that helps students understand complex topics easily. My goal is to build meaningful digital learning resources and inspire others through technology and teaching.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li><strong>Programming:</strong> C, Python, JavaScript</li>
      <li><strong>Web:</strong> HTML, CSS, Bootstrap, GitHub Pages</li>
      <li><strong>Tools:</strong> Git, GitHub, VS Code, Canva</li>
      <li><strong>Soft Skills:</strong> Training, Leadership, Public Speaking</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects-grid">

      <div class="project-card">
        <h3>1. Student Attendance Management System</h3>
        <p>Django-based digital attendance tracking system.</p>
        <a class="project-btn" href="#" target="_blank">View Project</a>
      </div>

      <div class="project-card">
        <h3>2. Personal Portfolio Website</h3>
        <p>This modern and responsive portfolio designed and hosted using GitHub Pages.</p>
        <a class="project-btn" href="#" target="_blank">Live Portfolio</a>
      </div>

    </div>
  </section>
</div>

<!-- RIGHT SIDEBAR -->
<div>
  <div class="sidebar-box">
    <h3>Contact Info</h3>
    <p><strong>Mobile:</strong> <br> +8801537690455</p>
    <p><strong>Email:</strong> <br> azmirauctc@gmail.com</p>
    <p><strong>Facebook:</strong> <br> <a href="https://www.facebook.com/share/19z165VkEb/" target="_blank">Profile Link</a></p>
    <p><strong>Instagram:</strong> <br> <a href="https://www.instagram.com/azmirakhanam.info" target="_blank">Instagram</a></p>
    <p><strong>GitHub:</strong> <br> <a href="https://github.com/AzmiraKhanam" target="_blank">github.com/AzmiraKhanam</a></p>
  </div>
</div>

<!-- CONTACT FORM -->
<section id="contact">
  <h2>Get In Touch</h2>
  <form class="contact-form" style="display:flex; flex-direction:column; gap:12px; max-width:500px;">
    <input type="text" placeholder="Your Name" required style="padding:10px; border-radius:8px; border:1px solid #ccc;">
    <input type="email" placeholder="Your Email" required style="padding:10px; border-radius:8px; border:1px solid #ccc;">
    <textarea rows="4" placeholder="Your Message" style="padding:10px; border-radius:8px; border:1px solid #ccc;"></textarea>
    <button type="submit" style="padding:10px; background:#0055b3; color:white; border:none; border-radius:8px; font-size:16px; cursor:pointer;">Send Message</button>
  </form>
</section>

  </div>  <footer>
    © 2025 Azmira Khanam | All Rights Reserved
  </footer></body>
</html>
