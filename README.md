<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Azmira Khanam | Personal Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      background: linear-gradient(135deg, #fdfbfb 0%, #ebedee 100%);
      color: #333;
    }

    header {
      background: linear-gradient(90deg, #ff9966, #ff5e62);
      color: white;
      text-align: center;
      padding: 25px 10px;
    }

    header h1 {
      font-size: 28px;
    }

    header p {
      font-size: 16px;
      opacity: 0.9;
    }

    .profile {
      text-align: center;
      margin-top: 30px;
    }

    .profile img {
      width: 130px;
      height: 130px;
      border-radius: 50%;
      border: 4px solid #ff9966;
    }

    .about, .skills, .contact {
      max-width: 700px;
      margin: 40px auto;
      padding: 20px;
      text-align: center;
      background: white;
      border-radius: 16px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    h2 {
      color: #ff7043;
      margin-bottom: 15px;
    }

    .about p {
      line-height: 1.6;
      font-size: 16px;
    }

    .skills ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      margin-top: 15px;
    }

    .skills li {
      background-color: #ffe0b2;
      padding: 8px 15px;
      border-radius: 20px;
      font-weight: 500;
    }

    .contact a {
      text-decoration: none;
      color: white;
      background: #ff9966;
      padding: 10px 20px;
      border-radius: 25px;
      margin: 6px;
      display: inline-block;
      transition: 0.3s;
    }

    .contact a:hover {
      background: #ff7043;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 15px 0;
      margin-top: 40px;
      font-size: 14px;
    }

    @media (max-width: 600px) {
      .skills ul {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>🌸 Azmira Khanam 🌸</h1>
    <p>Computer Engineering Student | Tech Enthusiast | Educator</p>
  </header>

  <section class="profile">
    <img src="https://i.ibb.co/2t7P2dL/profile.png" alt="Azmira Photo" />
  </section>

  <section class="about">
    <h2>About Me</h2>
    <p>
      Hi! I’m <b>Azmira Khanam</b>, a passionate Computer Engineering student from Bangladesh. 
      I love learning new technologies, teaching others, and creating beautiful digital experiences. 
      My goal is to inspire learners through creativity, simplicity, and innovation.
    </p>
  </section>

  <section class="skills">
    <h2>My Skills</h2>
    <ul>
      <li>HTML & CSS</li>
      <li>Python</li>
      <li>C Programming</li>
      <li>Machine Learning</li>
      <li>Teaching</li>
      <li>Content Creation</li>
    </ul>
  </section>

  <section class="contact">
    <h2>Get in Touch</h2>
    <a href="mailto:azmirauctc@gmail.com">📧 Email</a>
    <a href="https://www.facebook.com/share/19z165VkEb/" target="_blank">📘 Facebook</a>
    <a href="https://www.instagram.com/azmirakhanam.info?igsh=bnhuemt2andhc3F0" target="_blank">📸 Instagram</a>
    <a href="https://github.com/xyz" target="_blank">💻 GitHub</a>
  </section>

  <footer>
    © 2025 Azmira Khanam | Designed & Hosted with ❤️ on GitHub Pages
  </footer>
</body>
</html>
