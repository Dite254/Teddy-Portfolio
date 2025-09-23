<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Teddy Mwanzia | Home</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-image: url('assets/images/background.jpeg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      color: #fff;
    }

    .overlay {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0,0,0,0.6);
      z-index: -1;
    }

    header {
      padding: 1.5rem 2rem;
      background-color: rgba(0,0,0,0.7);
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-size: 1.8rem;
      margin: 0;
      letter-spacing: 1px;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 1.5rem;
      margin: 0;
      padding: 0;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s ease;
    }

    nav ul li a:hover {
      color: #fe6349;
    }

    .hero {
      text-align: center;
      padding: 6rem 2rem;
    }

    .hero h2 {
      font-size: 2.8rem;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.2rem;
      max-width: 700px;
      margin: 0 auto 2rem;
    }

    .cta-button {
      display: inline-block;
      padding: 0.75rem 1.5rem;
      background-color: #fe6349;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      transition: background-color 0.3s ease;
    }

    .cta-button:hover {
      background-color: #ff8267;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: rgba(0,0,0,0.7);
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <div class="overlay"></div>

  <header>
    <h1>Teddy Mwanzia</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="portfolio.html">Portfolio</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main class="hero">
    <h2>Creative Communications with Purpose</h2>
    <p>I’m Teddy Mwanzia, a communications professional passionate about storytelling, design, and digital strategy. Explore my work, learn my story, and let’s build something meaningful together.</p>
    <a href="portfolio.html" class="cta-button">View My Work</a>
  </main>

  <footer>
    <p>© 2025 Teddy Mwanzia | Built with passion in Kenya</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio | Teddy Mwanzia</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-image: url('assets/images/background.jpeg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      color: #fff;
    }

    .overlay {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0,0,0,0.6);
      z-index: -1;
    }

    header {
      padding: 1.5rem 2rem;
      background-color: rgba(0,0,0,0.7);
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-size: 1.8rem;
      margin: 0;
      letter-spacing: 1px;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 1.5rem;
      margin: 0;
      padding: 0;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s ease;
    }

    nav ul li a:hover {
      color: #fe6349;
    }

    .portfolio-section {
      text-align: center;
      padding: 4rem 2rem;
    }

    .portfolio-section h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    .portfolio-section p {
      font-size: 1.1rem;
      max-width: 700px;
      margin: 0 auto 2rem;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      padding: 2rem;
    }

    .card {
      background-color: rgba(255,255,255,0.1);
      border-radius: 10px;
      padding: 1rem;
      backdrop-filter: blur(5px);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: scale(1.05);
    }

    .card img {
      width: 100%;
      border-radius: 8px;
    }

    .card h3 {
      margin-top: 0.5rem;
      font-size: 1.2rem;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: rgba(0,0,0,0.7);
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <div class="overlay"></div>

  <header>
    <h1>Teddy Mwanzia</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="portfolio.html">Portfolio</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="portfolio-section">
    <h2>My Work</h2>
    <p>Here’s a curated selection of posters, visuals, and event content I’ve created—where strategy meets storytelling.</p>

    <div class="grid">
      <div class="card">
        <img src="assets/images/public-lecture.jpg" alt="Public Lecture Poster" />
        <h3>Public Lecture Poster</h3>
      </div>
      <div class="card">
        <img src="assets/images/alumni-breakfast.jpg" alt="Alumni Breakfast Poster" />
        <h3>Alumni Breakfast Poster</h3>
      </div>
      <!-- Add more cards as needed -->
    </div>
  </section>

  <footer>
    <p>© 2025 Teddy Mwanzia | Built with passion in Kenya</p>
  </footer>
</body>
</html>
