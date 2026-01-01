<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JeyaSurya M | Portfolio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Inter", system-ui, -apple-system, sans-serif;
    }

    body {
      background: linear-gradient(180deg, #020617, #020617);
      color: #e5e7eb;
      line-height: 1.7;
    }

    a {
      color: #38bdf8;
      text-decoration: none;
      font-weight: 600;
    }

    section {
      max-width: 1100px;
      margin: auto;
      padding: 70px 20px;
    }

    h1, h2, h3 {
      font-weight: 700;
    }

    h2 {
      color: #38bdf8;
      margin-bottom: 30px;
      font-size: 1.8rem;
    }

    /* HERO */
    .hero {
      text-align: center;
      padding-top: 100px;
    }

    .hero h1 {
      font-size: 3rem;
    }

    .hero span {
      color: #38bdf8;
    }

    .subtitle {
      margin-top: 12px;
      color: #94a3b8;
      font-size: 1.1rem;
      font-weight: 600;
    }

    .tagline {
      margin-top: 20px;
      font-size: 1.15rem;
      max-width: 700px;
      margin-inline: auto;
    }

    /* WHAT I DO */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 18px;
    }

    .card {
      background: #020617;
      border: 1px solid #1e293b;
      padding: 22px;
      border-radius: 14px;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-6px);
    }

    /* PROJECTS */
    .project {
      background: #020617;
      border: 1px solid #1e293b;
      padding: 24px;
      border-radius: 14px;
      margin-bottom: 18px;
    }

    .project h3 {
      color: #facc15;
      margin-bottom: 8px;
    }

    .project p {
      color: #cbd5f5;
    }

    .tech {
      display: inline-block;
      margin-top: 10px;
      font-size: 0.9rem;
      color: #94a3b8;
    }

    /* TECH STACK */
    .stack p {
      margin-bottom: 10px;
    }

    /* FOOTER */
    footer {
      text-align: center;
      padding: 50px 20px;
      border-top: 1px solid #1e293b;
      color: #94a3b8;
    }

    .quote {
      margin-top: 15px;
      font-style: italic;
      font-size: 0.95rem;
    }

    @media (max-width: 768px) {
      .hero h1 {
        font-size: 2.2rem;
      }
    }
  </style>
</head>

<body>

  <!-- HERO -->
  <section class="hero">
    <h1>👋 Hi, I’m <span>JeyaSurya M</span></h1>
    <p class="subtitle">Full Stack Developer | AI & ML Engineer | IoT Enthusiast</p>
    <p class="tagline">
      Building real-world, production-ready platforms with modern technologies.
    </p>
  </section>

  <!-- WHAT I DO -->
  <section>
    <h2>🚀 What I Do</h2>
    <div class="grid">
      <div class="card">🧠 Build AI & Machine Learning systems with real-world datasets</div>
      <div class="card">🌐 Develop full-stack platforms using Django, React & Next.js</div>
      <div class="card">⚙️ Design scalable APIs & automation systems</div>
      <div class="card">🔗 Deploy and maintain live production applications</div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section>
    <h2>🧩 Live Projects & Repositories</h2>

    <div class="project">
      <h3>Newsletter Platform</h3>
      <p>Production-ready newsletter platform for content delivery and audience growth.</p>
      <span class="tech">JavaScript</span><br>
      <a href="https://codex.learn-made.in" target="_blank">Live Demo →</a>
    </div>

    <div class="project">
      <h3>Lead Generator System</h3>
      <p>Automated lead generation system focused on conversions and scalability.</p>
      <span class="tech">JavaScript</span>
    </div>

    <div class="project">
      <h3>Chennai House Price Prediction (ML)</h3>
      <p>Predicts Chennai house prices using locality, BHK, square footage & market trends.</p>
      <span class="tech">Python · Machine Learning</span>
    </div>

    <div class="project">
      <h3>Stock Prediction Portal (ML)</h3>
      <p>ML-based stock prediction system built using historical market data.</p>
      <span class="tech">Python · Jupyter Notebook</span>
    </div>

    <div class="project">
      <h3>Face Attendance System</h3>
      <p>Face recognition–based attendance system with backend API architecture.</p>
      <span class="tech">JavaScript</span>
    </div>

    <div class="project">
      <h3>LearnMade Internship Platform</h3>
      <p>Internship platform for real-world project-based learning.</p>
      <a href="https://learn-made.in" target="_blank">Live Demo →</a>
    </div>

    <div class="project">
      <h3>Live Coding Challenge Platform</h3>
      <p>Competitive coding challenge platform for developers and students.</p>
      <a href="https://challenge.learn-made.in" target="_blank">Live Demo →</a>
    </div>

    <div class="project">
      <h3>SkillUp Learning Platform</h3>
      <p>Structured learning platform with skill paths and hands-on practice.</p>
      <a href="https://upskill.learn-made.in" target="_blank">Live Demo →</a>
    </div>

    <div class="project">
      <h3>30 Days – 30 Projects</h3>
      <p>30 real-world projects built in 30 days to showcase consistency.</p>
      <a href="https://project.learn-made.in" target="_blank">Live Demo →</a>
    </div>

  </section>

  <!-- TECH STACK -->
  <section class="stack">
    <h2>🛠 Tech Stack</h2>
    <p><strong>Languages:</strong> Python, JavaScript, TypeScript, C, C++</p>
    <p><strong>Frameworks:</strong> Django, FastAPI, Flask, React, Next.js, Node.js, Express.js</p>
    <p><strong>Databases & Tools:</strong> MongoDB, MySQL, Docker, Git</p>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>▶️ YouTube: <strong>LearnMade Academy</strong></p>
    <p class="quote">
      “Code is like humor. When you have to explain it, it’s bad.” — Cory House
    </p>
  </footer>

</body>
</html>
