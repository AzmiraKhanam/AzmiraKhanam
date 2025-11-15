<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Azmira Khanam | Portfolio</title>
  <style>
    :root{
      --primary:#0055b3;
      --accent:#4A90E2;
      --muted:#6b7280;
      --card:#ffffff;
      --bg:#f0f4ff;
    }
    *{box-sizing:border-box}
    body {
      font-family: "Poppins", sans-serif;
      margin: 0;
      padding: 0;
      background: var(--bg);
      color: #111827;
      -webkit-font-smoothing:antialiased;
    }/* NAVBAR */
.navbar {
  background: var(--primary);
  padding: 12px 20px;
  display: flex;
  justify-content: center;
  gap: 28px;
  position: sticky;
  top: 0;
  z-index: 100;
  box-shadow: 0 6px 18px rgba(5,70,120,0.15);
}
.navbar a { color: white; text-decoration:none; font-weight:600; }

/* HERO */
.hero {
  background: linear-gradient(180deg,var(--primary),var(--accent));
  color: white;
  padding: 72px 20px 120px;
  text-align: center;
}
.hero h1{font-size:44px;margin:0 0 8px}
.hero p{font-size:18px;margin:0;opacity:.95}

/* PROFILE */
.profile-pic{display:flex;justify-content:center;margin-top:-100px}
.profile-pic img{width:190px;height:190px;border-radius:50%;border:6px solid white;box-shadow:0 10px 30px rgba(2,6,23,0.18);background:#fff;object-fit:cover}

/* LAYOUT */
.layout{max-width:1180px;margin:30px auto;display:grid;grid-template-columns: 1fr 360px;gap:28px;padding:0 20px}

/* SECTIONS */
.card{background:var(--card);padding:22px;border-radius:14px;box-shadow:0 6px 22px rgba(12,15,30,0.06)}
h2{color:var(--primary);margin:0 0 14px;font-size:22px}
p{line-height:1.6;color:#374151}
ul{padding-left:18px;color:#374151}
li{margin-bottom:8px}

/* MAIN CONTENT SPECIFIC */
.about .meta{color:var(--muted);margin-top:8px}
.quick-bio{display:flex;gap:12px;flex-wrap:wrap}
.quick-bio .pill{background:#f4f8ff;padding:8px 12px;border-radius:999px;border:1px solid #e8f0ff;color:var(--primary);font-weight:600}

/* SKILLS */
.skills{display:flex;gap:10px;flex-wrap:wrap}
.skill-b{background:#f8fafc;padding:8px 12px;border-radius:10px;border:1px solid #eef2ff;font-weight:600;color:#0f172a}

/* PROJECTS */
.projects-grid{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.project-card{background:#f8fbff;padding:14px;border-radius:12px;border-left:5px solid var(--primary)}
.project-card h3{margin:0 0 6px;color:var(--primary)}
.project-card p{margin:0}
.project-actions{margin-top:10px}
.btn{display:inline-block;padding:8px 12px;border-radius:8px;text-decoration:none;font-weight:700}
.btn-primary{background:var(--primary);color:white}
.btn-outline{border:1px solid var(--primary);color:var(--primary);background:transparent}

/* SIDEBAR */
.sidebar .box{margin-bottom:16px}
.contact-box p{margin:6px 0}
.socials{display:flex;gap:8px;flex-wrap:wrap}
.socials a{display:inline-block;padding:8px;border-radius:8px;border:1px solid rgba(0,0,0,0.06);text-decoration:none}

/* EXPERIENCE / EDUCATION */
.timeline{display:flex;flex-direction:column;gap:12px}
.timeline .item{padding:12px;border-radius:10px;background:#fbfdff;border:1px solid #eef6ff}
.small{font-size:13px;color:var(--muted)}

/* CERTIFICATES */
.cert-list{display:flex;flex-direction:column;gap:8px}

/* CONTACT FORM (sidebar) */
form.contact-form{display:flex;flex-direction:column;gap:10px}
form.contact-form input, form.contact-form textarea{padding:10px;border-radius:8px;border:1px solid #e5e7eb}
form.contact-form button{padding:10px;border-radius:8px;border:none;background:var(--primary);color:white;font-weight:700;cursor:pointer}

/* FOOTER */
footer{background:var(--primary);color:white;padding:20px;text-align:center;border-top:4px solid var(--accent);margin-top:28px}

/* RESPONSIVE */
@media(max-width:1000px){
  .projects-grid{grid-template-columns:1fr}
  .layout{grid-template-columns:1fr 320px}
}
@media(max-width:820px){
  .layout{grid-template-columns:1fr}
  .profile-pic{margin-top:-70px}
  .hero{padding-bottom:80px}
}

  </style>
</head>
<body>
  <div class="navbar">
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#experience">Experience</a>
    <a href="#contact">Contact</a>
  </div>  <header class="hero">
    <h1>Azmira Khanam</h1>
    <p>Computer Engineering Student | Educator | Ex–Deputy Chief (Training), Red Crescent Youth CTG</p>
  </header>  <div class="profile-pic">
    <img src="https://raw.githubusercontent.com/AzmiraKhanam/AzmiraKhanam/refs/heads/main/formal%20photo.jpg" alt="Azmira Khanam">
  </div>  <main class="layout">
    <!-- LEFT / MAIN -->
    <div>
      <section id="about" class="card about">
        <h2>About Me</h2>
        <p>Hi! I’m <strong>Azmira Khanam</strong> — a final-year B.Sc. Computer Engineering student from Chattogram, Bangladesh. I’m passionate about teaching, web development and using technology to build educational content that makes learning easy for students.</p>
        <p class="meta">📍 Chattogram, Bangladesh • ✉️ azmirauctc@gmail.com • 📞 +8801537690455</p>
      </section><section class="card" id="quickbio">
    <h2>Quick Bio</h2>
    <div class="quick-bio">
      <div class="pill">Final-year CSE Student</div>
      <div class="pill">Educator & Content Creator</div>
      <div class="pill">Ex–Deputy Chief, RCY CTG</div>
      <div class="pill">AI & Web Enthusiast</div>
    </div>
  </section>

  <section class="card" id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div class="skill-b">C</div>
      <div class="skill-b">Python</div>
      <div class="skill-b">JavaScript</div>
      <div class="skill-b">HTML & CSS</div>
      <div class="skill-b">Django</div>
      <div class="skill-b">Git & GitHub</div>
    </div>
  </section>

  <section class="card" id="projects">
    <h2>Projects</h2>
    <div class="projects-grid">
      <div class="project-card">
        <h3>Student Attendance Management System</h3>
        <p>Django-based web app to manage student attendance, reports and analytics for teachers.</p>
        <div class="project-actions"><a class="btn btn-primary" href="#">View</a> <a class="btn btn-outline" href="#">Source</a></div>
      </div>

      <div class="project-card">
        <h3>Personal Portfolio Website</h3>
        <p>A clean, responsive portfolio built with HTML/CSS and hosted on GitHub Pages.</p>
        <div class="project-actions"><a class="btn btn-primary" href="#">Live</a> <a class="btn btn-outline" href="#">Code</a></div>
      </div>

      <div class="project-card">
        <h3>Facebook Sentiment Analysis (Thesis)</h3>
        <p>Ensemble model combining RoBERTa + LSTM/BiLSTM/GRU for sentiment classification on social media comments.</p>
        <div class="project-actions"><a class="btn btn-primary" href="#">Paper</a> <a class="btn btn-outline" href="#">Dataset</a></div>
      </div>

      <div class="project-card">
        <h3>Simple Weather App</h3>
        <p>JavaScript app using open weather API to show current weather and forecasts.</p>
        <div class="project-actions"><a class="btn btn-primary" href="#">Open</a> <a class="btn btn-outline" href="#">Repo</a></div>
      </div>

    </div>
  </section>

  <section class="card" id="experience">
    <h2>Experience</h2>
    <div class="timeline">
      <div class="item">
        <strong>Deputy Chief (Training) — Red Crescent Youth, Chittagong</strong>
        <div class="small">Role: Organised training programs, led volunteer training sessions, managed training calendar.</div>
      </div>

      <div class="item">
        <strong>Tutor & Content Creator</strong>
        <div class="small">Role: Created beginner-friendly lessons in programming and web development. Conducted live sessions and created notes.</div>
      </div>
    </div>
  </section>

</div>

<!-- RIGHT / SIDEBAR -->
<aside class="sidebar">
  <div class="card sidebar-box contact-box">
    <h3>Contact</h3>
    <p><strong>Mobile:</strong><br>+8801537690455</p>
    <p><strong>Email:</strong><br><a href="mailto:azmirauctc@gmail.com">azmirauctc@gmail.com</a></p>
    <div class="socials">
      <a href="https://github.com/AzmiraKhanam" target="_blank">GitHub</a>
      <a href="https://www.facebook.com/share/19z165VkEb/" target="_blank">Facebook</a>
      <a href="https://www.instagram.com/azmirakhanam.info" target="_blank">Instagram</a>
    </div>
  </div>

  <div class="card sidebar-box">
    <h3>Education</h3>
    <p><strong>B.Sc. in Computer Science & Engineering</strong><br>University of Creative Technology, Chattogram (Final Semester)</p>
  </div>

  <div class="card sidebar-box">
    <h3>Achievements</h3>
    <ul class="cert-list">
      <li>Led 30+ volunteer trainings at RCY CTG</li>
      <li>Presented at inter-university programming events</li>
      <li>Completed multiple web & AI workshops</li>
    </ul>
  </div>

  <div class="card sidebar-box">
    <h3>Certificates</h3>
    <ul class="cert-list">
      <li>Web Development Basics</li>
      <li>Leadership & Training Certificate — RCY</li>
      <li>Python for Data Science</li>
    </ul>
  </div>

  <div class="card sidebar-box">
    <h3>Send a message</h3>
    <form class="contact-form" action="https://formspree.io/f/mrgrwqzd" method="POST">
      <input type="text" name="name" placeholder="Your name" required>
      <input type="email" name="email" placeholder="Your email" required>
      <textarea name="message" rows="4" placeholder="Your message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </div>

</aside>

<!-- CONTACT SECTION (expanded) -->
<div style="grid-column:1/ -1;">
  <section class="card" id="contact-expanded">
    <h2>Get In Touch</h2>
    <p>If you want to collaborate, hire, or just say hello — drop a message using the form or email me at <a href="mailto:azmirauctc@gmail.com">azmirauctc@gmail.com</a>. I usually reply within a few days.</p>
  </section>
</div>

  </main>  <footer>
    © 2025 Azmira Khanam — Designed with ❤️ from Chattogram
  </footer>
</body>
</html>
