
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Personal website of Abdul Aziz Samy" />
  <title>Abdul Aziz Samy</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <script>
    function toggleTheme() {
      document.body.classList.toggle("dark");
    }
  </script>
  <style>
    :root {
      --bg: #f9f9f9;
      --text: #333;
      --card-bg: #fff;
    }
    body.dark {
      --bg: #1e1e1e;
      --text: #f5f5f5;
      --card-bg: #2c2c2c;
    }
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: var(--bg);
      color: var(--text);
      transition: background 0.3s, color 0.3s;
    }
    header {
      background: var(--card-bg);
      padding: 2rem;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }
    header img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid var(--text);
    }
    h1 {
      margin: 1rem 0 0.5rem;
      font-size: 2rem;
    }
    .quote {
      font-style: italic;
      color: #888;
    }
    .theme-toggle {
      position: absolute;
      top: 1rem;
      right: 1rem;
      background: none;
      border: 2px solid var(--text);
      padding: 0.5rem 1rem;
      cursor: pointer;
      color: var(--text);
      border-radius: 8px;
    }
    main {
      max-width: 700px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    section {
      margin-bottom: 2rem;
    }
    h2 {
      font-size: 1.5rem;
      margin-bottom: 0.5rem;
    }
    .contact-btn {
      display: inline-block;
      padding: 0.75rem 1.5rem;
      background: #0066cc;
      color: #fff;
      text-decoration: none;
      border-radius: 6px;
      font-weight: 600;
      transition: background 0.3s;
    }
    .contact-btn:hover {
      background: #004999;
    }
    footer {
      text-align: center;
      padding: 2rem 0;
      font-size: 0.9rem;
      color: #777;
    }
  </style>
</head>
<body>
  <button class="theme-toggle" onclick="toggleTheme()">Toggle Theme</button>
  <header>
    <img src="photo.jpg" alt="Abdul Aziz Samy" />
    <h1>Abdul Aziz Samy</h1>
    <p class="quote">“Every idea starts small — I just give mine the courage to grow.”</p>
  </header>
  <main>
    <section>
      <h2>About Me</h2>
      <p>I’m a Bangladeshi student of class twelve, CEO of Gadget Vai, and a News Writer & Researcher at Narsingdi Biggan Club. Passionate about tech, science communication, and youth innovation, I aim to inspire and connect through digital creativity.</p>
    </section>
    <section>
      <h2>Contact</h2>
      <a class="contact-btn" href="mailto:your-email@example.com" target="_blank">📧 Contact Me</a>
      <p style="margin-top: 1rem;">
        <a href="https://www.facebook.com/aziz.samy.507" target="_blank">Facebook</a> |
        <a href="https://www.instagram.com/___thebadsoul___" target="_blank">Instagram</a>
      </p>
    </section>
  </main>
  <footer>
    &copy; 2025 Abdul Aziz Samy. All rights reserved.
  </footer>
</body>
</html>
