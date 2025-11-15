<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Azmira Khanam | Portfolio</title>

  <style>
    body {
      font-family: "Poppins", sans-serif;
      margin: 0;
      padding: 0;
      background: #ffffff;
      color: #222;
    }

    /* HEADER */
    header {
      background-color: #1f4e8c;
      color: white;
      padding: 60px 10px;
      text-align: center;
      border-bottom: 4px solid #4A90E2;
    }
    header h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }
    header p {
      font-size: 20px;
      color: #dbeafe;
      max-width: 900px;
      margin: auto;
    }

    /* PROFILE IMAGE */
    .profile {
      display: flex;
      justify-content: center;
      margin-top: -50px;
    }
    .profile img {
      width: 170px;
      height: 170px;
      border-radius: 50%;
      border: 5px solid #4A90E2;
      background: white;
    }

    /* MAIN CONTAINER */
    .container {
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 20px;
    }

    /* SECTIONS */
    section {
      background: #f9f9f9;
      padding: 35px;
      margin-bottom: 35px;
      border-radius: 18px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.08);
    }

    h2 {
      color: #1f4e8c;
      margin-bottom: 20px;
      text-transform: uppercase;
      font-size: 26px;
      text-align: center;
      letter-spacing: 1px;
    }

    ul li {
      margin-bottom: 10px;
      font-size: 17px;
    }

    /* PROJECT CARDS – DESKTOP BEAUTIFUL */
    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(330px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .project-card {
      background: white;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.07);
      border-left: 5px solid #1f4e8c;
      transition: 0.3s;
    }
    .project-card:hover {
      transform: translateY(-5px);
    }

    .project-card h3 {
      margin-top: 0;
      color: #1f4e8c;
    }

    .project-btn {
      display: inline-block;
      padding: 10px 20px;
      background-color: #1f4e8c;
      color: white;
      border-radius: 25px;
      text-decoration: none;
      transition: 0.3s;
      margin-top: 10px;
    }
    .project-btn:hover {
      background-color: #003366;
    }

    /* CONTACT FORM SECTION */
    form.contact-form {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 15px;
      margin-top: 25px;
    }
    .full { grid-column: 1 / -1; }

    label {
      font-weight: 600;
      margin-bottom: 6px;
      display: block;
    }

    input, textarea {
      width: 100%;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 10px;
      font-size: 16px;
    }
    textarea {
      resize: vertical;
      min-height: 120px;
    }

    .btn-submit {
      grid-column: 1 / -1;
      background: #1f4e8c;
      color: white;
      padding: 14px;
      border: none;
      font-size: 17px;
      border-radius: 12px;
      cursor: pointer;
      font-weight: 700;
      transition: 0.3s;
    }
    .btn-submit:hover {
      background: #003366;
    }

    /* FOOTER */
    footer {
      background: #1f4e8c;
      color: white;
      text-align: center;
      padding: 25px 10px;
      margin-top: 40px;
      border-top: 4px solid #4A90E2;
    }

    /* RESPONSIVE */
    @media (max-width: 700px) {
      header h1 { font-size: 34px; }
      header p { font-size: 16px; padding: 0 10px; }

      form.contact-form { grid-template-columns: 1fr; }
    }
  </style>
</head>

<body>

  <header>
    <h1>Azmira Khanam</h1>
    <p>Computer Engineering Student | Educator | Ex–Deputy Chief (Training), Red Crescent Youth CTG</p>
  </header>

  <div class="profile">
    <img src="https://raw.githubusercontent.com/AzmiraKhanam/AzmiraKhanam/refs/heads/main/formal%20photo.jpg" alt="Azmira Khanam">
  </div>

  <div class="container">

    <section>
      <h2>About Me</h2>
      <p>
        Hi! I’m <strong>Azmira Khanam</strong> — a final-year B.Sc. Engineering student passionate about technology, education, and leadership.
        I previously served as the <strong>Deputy Chief (Training Department)</strong> at Red Crescent Youth, Chittagong.
        My aim is to blend engineering knowledge with teaching to create digital learning content that helps others learn easily.
        <br><br>
        📍 <strong>Location:</strong> Chattogram, Bangladesh
      </p>
    </section>

    <section>
      <h2>Quick Bio</h2>
      <ul>
        <li>🎓 B.Sc. in Computer Science & Engineering (Last Semester)</li>
        <li>❤️ Passionate about teaching & content creation</li>
        <li>👩‍🏫 Ex–Deputy Chief of Training, Red Crescent Youth CTG</li>
        <li>💻 Web development & backend basics learner</li>
        <li>🌍 Interested in AI, Cloud Computing & Machine Learning</li>
      </ul>
    </section>

    <section>
      <h2>Skills</h2>
      <ul>
        <li><strong>Programming:</strong> C, Python, JavaScript</li>
        <li><strong>Web:</strong> HTML, CSS, Bootstrap, GitHub Pages</li>
        <li><strong>Tools:</strong> Git, GitHub, VS Code, Canva</li>
        <li><strong>Soft Skills:</strong> Training, Leadership, Public Speaking</li>
        <li><strong>Interests:</strong> AI, ML, Web Dev, Cloud</li>
      </ul>
    </section>

    <section>
      <h2>Projects</h2>

      <div class="projects-grid">

        <div class="project-card">
          <h3>1. Student Attendance Management System (Web-Based)</h3>
          <p>A Django-based system that helps teachers manage student attendance digitally with accuracy.</p>
          <a href="#" class="project-btn" target="_blank">🔗 View Project</a>
        </div>

        <div class="project-card">
          <h3>2. Personal Portfolio Website</h3>
          <p>This website is built and hosted using GitHub Pages. Fully responsive with a modern UI.</p>
          <a href="#" class="project-btn" target="_blank">🔗 Live Portfolio</a>
        </div>

      </div>
    </section>

    <section>
      <h2>Get In Touch</h2>
      <p>📞 <strong>Mobile:</strong> <a href="tel:+8801537690455">+8801537690455</a></p>
      <p>📧 <strong>Email:</strong> <a href="mailto:azmirauctc@gmail.com">azmirauctc@gmail.com</a></p>
      <p>🌐 <strong>Facebook:</strong> <a href="https://www.facebook.com/share/19z165VkEb/" target="_blank">Facebook Profile</a></p>
      <p>📸 <strong>Instagram:</strong> <a href="https://www.instagram.com/azmirakhanam.info" target="_blank">Instagram Profile</a></p>
      <p>💻 <strong>GitHub:</strong> <a href="https://github.com/AzmiraKhanam" target="_blank">github.com/AzmiraKhanam</a></p>

      <!-- Formspree Contact Form -->
      <form class="contact-form" action="https://formspree.io/f/mrgrwqzd" method="POST">
        <div>
          <label>Full Name</label>
          <input name="name" type="text" placeholder="Your full name" required>
        </div>
        <div>
          <label>Mobile</label>
          <input name="phone" type="text" placeholder="+8801XXXXXXXXX" required>
        </div>
        <div class="full">
          <label>Email</label>
          <input name="email" type="email" placeholder="you@example.com" required>
        </div>
        <div class="full">
          <label>Message</label>
          <textarea name="message" placeholder="Write your message..." required></textarea>
        </div>

        <button type="submit" class="btn-submit">Send Message</button>
      </form>
    </section>

  </div>

  <footer>
    <p>© 2025 Azmira Khanam | All Rights Reserved</p>
    <p>Designed with ❤️ from Chattogram, Bangladesh</p>
  </footer>

</body>
</html>
