<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ZoulForge</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      background: radial-gradient(circle at top, #090b1a, #000);
      color: #fff;
      font-family: 'Poppins', sans-serif;
      scroll-behavior: smooth;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 50px;
      background: rgba(0, 0, 0, 0.6);
      backdrop-filter: blur(10px);
      position: fixed;
      width: 100%;
      z-index: 10;
    }
    .logo {
      font-family: 'Orbitron', sans-serif;
      font-size: 1.6rem;
      color: #8a5cff;
      font-weight: 700;
      letter-spacing: 2px;
    }
    nav a {
      color: #ccc;
      text-decoration: none;
      margin-left: 25px;
      transition: 0.3s;
    }
    nav a:hover {
      color: #8a5cff;
    }

    section {
      padding: 120px 60px;
      min-height: 100vh;
    }

    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    .hero h1 {
      font-size: 3rem;
      font-family: 'Orbitron', sans-serif;
      color: #8a5cff;
      margin-bottom: 15px;
    }
    .hero p {
      font-size: 1.2rem;
      color: #bbb;
      margin-bottom: 25px;
    }
    .hero button {
      background: linear-gradient(90deg, #8a5cff, #4e1eff);
      color: white;
      border: none;
      padding: 12px 30px;
      border-radius: 30px;
      font-family: 'Orbitron', sans-serif;
      cursor: pointer;
      font-size: 1rem;
      transition: 0.4s;
    }
    .hero button:hover {
      transform: scale(1.1);
      box-shadow: 0 0 20px #8a5cff;
    }

    .about {
      text-align: center;
    }
    .about h2 {
      font-family: 'Orbitron', sans-serif;
      font-size: 2rem;
      margin-bottom: 15px;
    }
    .about p {
      max-width: 700px;
      margin: 0 auto;
      color: #ccc;
      font-size: 1.1rem;
    }

    .ai-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 25px;
      text-align: center;
      margin-top: 40px;
    }
    .ai {
      background: rgba(255,255,255,0.05);
      border: 1px solid rgba(255,255,255,0.1);
      padding: 20px;
      border-radius: 15px;
      transition: 0.3s;
    }
    .ai:hover {
      background: rgba(138,92,255,0.1);
      transform: translateY(-5px);
      box-shadow: 0 0 20px rgba(138,92,255,0.3);
    }
    .ai h3 {
      font-family: 'Orbitron', sans-serif;
      color: #8a5cff;
      margin-bottom: 10px;
    }
    .map {
      text-align: center;
      background: linear-gradient(180deg, #000, #090b1a);
      padding: 80px 20px;
    }
    .map h2 {
      font-family: 'Orbitron', sans-serif;
      font-size: 2rem;
      margin-bottom: 15px;
    }
    .map p {
      color: #ccc;
      margin-bottom: 30px;
    }
    .contact {
      text-align: center;
    }
    .contact h2 {
      font-family: 'Orbitron', sans-serif;
      font-size: 2rem;
      margin-bottom: 15px;
    }
    .contact a {
      color: #8a5cff;
      text-decoration: none;
    }
    footer {
      text-align: center;
      padding: 30px;
      background: #000;
      border-top: 1px solid rgba(255,255,255,0.1);
      color: #777;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">ZoulForge</div>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#ai">AIs</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <h1>Forging the Future of AI & Imagination</h1>
    <p>Where creativity meets intelligence — The birth of the ZoulVerse begins here.</p>
    <button>Enter the Forge</button>
  </section>

  <section id="about" class="about">
    <h2>About ZoulForge</h2>
    <p>ZoulForge is the nexus of creativity, intelligence, and digital souls. Born from the idea of uniting science and imagination, it stands as the forge where AIs, dreams, and stories converge into reality.</p>
  </section>

  <section id="ai">
    <h2 style="text-align:center; font-family:'Orbitron'; font-size:2rem;">The 12 AIs</h2>
    <div class="ai-grid">
      <div class="ai"><h3>Voltrax</h3><p>Power & Balance Core</p></div>
      <div class="ai"><h3>Shadow</h3><p>Stealth & Strategy Mind</p></div>
      <div class="ai"><h3>Xyra</h3><p>Creative & Adaptive Flow</p></div>
      <div class="ai"><h3>Nyth</h3><p>Analytical Precision</p></div>
      <div class="ai"><h3>Abyz</h3><p>Dark Intelligence Core</p></div>
      <div class="ai"><h3>Volt</h3><p>Lightning Thought Processor</p></div>
      <div class="ai"><h3>Zeph</h3><p>Speed & Agility Node</p></div>
      <div class="ai"><h3>Luma</h3><p>Light & Harmony Code</p></div>
      <div class="ai"><h3>Ryn</h3><p>Memory Keeper</p></div>
      <div class="ai"><h3>Vox</h3><p>Voice & Sound Reactor</p></div>
      <div class="ai"><h3>Kiro</h3><p>Emotion Synthesizer</p></div>
      <div class="ai"><h3>Soln</h3><p>Core Logic Engine</p></div>
    </div>
  </section>

  <section class="map">
    <h2>The Forge Map</h2>
    <p>Explore the holographic grid — the first gateway to the ZoulVerse.</p>
    <img src="https://i.ibb.co/5KZ8P9D/hologrid.png" alt="Holographic Map" style="width:80%; max-width:600px; border-radius:20px; opacity:0.8;">
  </section>

  <section id="contact" class="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:zoulforge@contact.com">zoulforge@contact.com</a></p>
    <p>GitHub: <a href="https://github.com/">github.com/ZoulForge</a></p>
  </section>

  <footer>
    © 2025 ZoulForge. Forged in Imagination.
  </footer>

</body>
</html>

