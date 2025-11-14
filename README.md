<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      font-family: "Poppins", sans-serif;
      margin: 0;
      padding: 0;
      background: #ffffff;
      color: #222;
      text-align: center;
    }

    header {
      background-color: #1f4e8c;
      color: white;
      padding: 40px 10px;
      border-bottom: 4px solid #4A90E2;
    }

    header h1 {
      font-size: 34px;
      margin-bottom: 5px;
    }

    header p {
      font-size: 18px;
      color: #dbeafe;
    }

    img {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      margin-top: 25px;
      border: 4px solid #4A90E2;
    }

    section {
      max-width: 750px;
      margin: 40px auto;
      padding: 30px;
      background: #f9f9f9;
      border-radius: 20px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.08);
      text-align: left;
    }

    h2 {
      color: #1f4e8c;
      margin-bottom: 15px;
      text-transform: uppercase;
      letter-spacing: 1px;
      text-align: center;
    }

    ul li {
      margin-bottom: 8px;
    }

    a {
      text-decoration: none;
      color: #1f4e8c;
      font-weight: bold;
    }

    a:hover {
      color: #003366;
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

    /* Contact form styles */
    form.contact-form {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
      align-items: start;
      margin-top: 20px;
    }

    .contact-form .full { grid-column: 1 / -1; }

    label { display: block; font-size: 14px; margin-bottom: 6px; color: #111; }
    input[type="text"], input[type="email"], textarea {
      width: 100%; padding: 10px 12px; border: 1px solid #ddd; border-radius: 8px;
      font-size: 15px; box-sizing: border-box;
    }
    textarea { min-height: 100px; resize: vertical; }

    .btn-submit {
      grid-column: 1 / -1;
      display: inline-block; padding: 12px 20px; background: #1f4e8c; color: #fff;
      border: none; border-radius: 10px; font-weight: 700; cursor: pointer;
      text-align: center;
    }
    .btn-submit:hover { background: #003366; transition: 0.2s; }

    footer {
      margin-top: 50px;
      background: #1f4e8c;
      color: white;
      padding: 20px;
      border-top: 4px solid #4A90E2;
      text-align: center;
    }

    footer p {
      font-size: 14px;
      margin: 5px 0;
    }

    /* Responsive */
    @media (max-width: 700px) {
      form.contact-form { grid-template-columns: 1fr; }
    }

  </style>
</head>

<body>

  <header>
    <h1>Azmira Khanam</h1>
    <p>Computer Engineering Student | Educator | Ex–Deputy Chief (Training), Red Crescent Youth CTG</p>
  </header>

  <img src="https://raw.githubusercontent.com/AzmiraKhanam/AzmiraKhanam/refs/heads/main/formal%20photo.jpg" alt="Azmira Khanam">

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

    <h3>1. Student Attendance Management System (Web-Based)</h3>
    <p>A Django-based system that helps teachers manage student attendance digitally with accuracy.</p>
    <a href="#" class="project-btn" target="_blank">🔗 View Project</a>

    <br><br>

    <h3>2. Personal Portfolio Website</h3>
    <p>This website is built and hosted using GitHub Pages. Fully responsive with a modern UI.</p>
    <a href="#" class="project-btn" target="_blank">🔗 Live Portfolio</a>

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
        <label for="name">Full Name</label>
        <input id="name" name="name" type="text" placeholder="Your full name" required>
      </div>

      <div>
        <label for="phone">Mobile</label>
        <input id="phone" name="phone" type="text" placeholder="+8801XXXXXXXXX" required>
      </div>

      <div class="full">
        <label for="email">Email</label>
        <input id="email" name="email" type="email" placeholder="you@example.com" required>
      </div>

      <div class="full">
        <label for="message">Message</label>
        <textarea id="message" name="message" placeholder="Write your message..." required></textarea>
      </div>

      <button type="submit" class="btn-submit">Send Message</button>
    </form>
    <p style="font-size:13px; color:#666; margin-top:8px;">Form powered by Formspree (direct email delivery)</p>
  </section>

  <footer>
    <p>© 2025 Azmira Khanam | All Rights Reserved</p>
    <p>Designed with ❤️ from Chattogram, Bangladesh</p>
  </footer>

</body>
</html>
