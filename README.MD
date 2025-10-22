<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>MUHAMMAD SHOAIB | Developer Portfolio</title>
    <style>
      * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
        font-family: 'Poppins', sans-serif;
      }

      body {
        background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
        color: white;
        min-height: 100vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
      }

      header {
        text-align: center;
        margin-bottom: 2rem;
      }

      h1 {
        font-size: 2.8rem;
        letter-spacing: 2px;
      }

      h2 {
        font-weight: 400;
        color: #00c6ff;
        margin-top: 10px;
      }

      .social-links {
        display: flex;
        gap: 20px;
        margin-top: 15px;
        justify-content: center;
      }

      .social-links a {
        color: #fff;
        text-decoration: none;
        font-size: 1.2rem;
        transition: color 0.3s;
      }

      .social-links a:hover {
        color: #00c6ff;
      }

      .container {
        background: rgba(255, 255, 255, 0.08);
        border-radius: 20px;
        padding: 40px;
        width: 90%;
        max-width: 800px;
        box-shadow: 0 0 15px rgba(0, 0, 0, 0.3);
        animation: fadeIn 1.2s ease;
      }

      section {
        margin-bottom: 30px;
      }

      section h3 {
        color: #00c6ff;
        margin-bottom: 10px;
        border-bottom: 2px solid #00c6ff;
        display: inline-block;
        padding-bottom: 5px;
      }

      p, li {
        line-height: 1.6;
        color: #dcdcdc;
      }

      ul {
        list-style: square inside;
      }

      .projects a {
        color: #00c6ff;
        text-decoration: none;
      }

      .projects a:hover {
        text-decoration: underline;
      }

      footer {
        margin-top: 40px;
        color: #999;
        font-size: 0.9rem;
      }

      @keyframes fadeIn {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
      }
    </style>
  </head>
  <body>
    <header>
      <h1>MUHAMMAD SHOAIB</h1>
      <h2>Oracle APEX Developer | Web Developer</h2>
      <div class="social-links">
        <a href="mailto:shoaib.khan44123@gmail.com">📧 Email</a>
        <a href="https://github.com/MuhammadShoaib44123-cloud" target="_blank">💻 GitHub</a>
      </div>
    </header>

    <div class="container">
      <section class="about">
        <h3>About Me</h3>
        <p>
          I’m MUHAMMAD SHOAIB, a passionate Oracle APEX and Web Developer who loves building
          efficient, user-friendly, and visually appealing applications. My work focuses on blending database
          power with modern front-end experiences.
        </p>
      </section>

      <section class="skills">
        <h3>Skills</h3>
        <ul>
          <li>Oracle APEX Development</li>
          <li>SQL / PL/SQL</li>
          <li>HTML, CSS, JavaScript, React</li>
          <li>Database Triggers, Procedures & Functions</li>
        </ul>
      </section>

      <section class="projects">
        <h3>Projects</h3>
        <p>
          🔹 <strong>POS Application:</strong>
          <a href="https://oracleapex.com/ords/r/smit_project/pos283288/login?session=31209286897955" target="_blank">
            View Project
          </a>
        </p>
        <p>
          🔹 More projects available on my
          <a href="https://github.com/MuhammadShoaib44123-cloud" target="_blank">GitHub Profile</a>.
        </p>
      </section>

      <section class="contact">
        <h3>Contact</h3>
        <p>
          💌 Email: <a href="mailto:shoaib.khan44123@gmail.com">shoaib.khan44123@gmail.com</a>
        </p>
      </section>
    </div>

    <footer>
      © 2025 MUHAMMAD SHOAIB | All Rights Reserved
    </footer>
  </body>
</html>
