<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Digital Craft Inc</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f9fafb;
      margin: 0;
      color: #1f2937;
    }
    header, footer {
      background-color: white;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      padding: 20px;
      text-align: center;
    }
    nav a {
      margin: 0 10px;
      color: #3b82f6;
      text-decoration: none;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      padding: 20px;
    }
    section {
      margin-bottom: 40px;
    }
    h1, h2 {
      color: #111827;
    }
    ul {
      list-style-type: disc;
      padding-left: 20px;
    }
    a.email {
      color: #2563eb;
    }
  </style>
</head>
<body>

  <header>
    <h1>Digital Craft Inc</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About Us</h2>
      <p>
        Welcome to Digital Craft Inc! We provide tech-based solutions for businesses and individuals — from web and app development to custom software, game apps, and live broadcast channels.
        Led by CEO <strong>Syed Junaid Gillani</strong>.
      </p>
    </section>

    <section id="services">
      <h2>Our Services</h2>
      <ul>
        <li>Web Development</li>
        <li>App Development (Android & iOS)</li>
        <li>Custom Tech Solutions</li>
        <li>Game & Software Development</li>
        <li>Live Broadcast Channel Setup</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p>Email: <a class="email" href="mailto:digitalcraft48@gmail.com">digitalcraft48@gmail.com</a></p>
    </section>
  </main>

  <footer>
    &copy; <span id="year"></span> Digital Craft Inc. All rights reserved.
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>

</body>
</html>
