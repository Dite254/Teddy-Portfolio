# Teddy-Portfolio<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Teddy Mwanzia | Communications Portfolio</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <nav>
      <h1>Teddy Mwanzia</h1>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="portfolio.html">Portfolio</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="skills.html">Skills</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h2>Creative Communicator. Visual Storyteller. Growth Strategist.</h2>
    <p>Welcome to my portfolio—where strategy meets creativity.</p>
    <a href="portfolio.html" class="cta-button">View My Work</a>
  </section>

  <footer>
    <p>© 2025 Teddy Mwanzia | Built with passion in Kenya</p>
  </footer>
</body>
</html>
<div class="overlay"></div>
<div class="gallery">
  <div class="project">
    <img src="assets/images/public-lecture.jpg" alt="Public Lecture Poster" />
    <h3>Public Lecture: Leadership for Sustainability</h3>
    <p>Designed for ILU’s climate action lecture featuring Dr. Solomon Njenga.</p>
  </div>

  <div class="project">
    <img src="assets/images/alumni-breakfast.jpg" alt="Alumni Prayer Breakfast Poster" />
    <h3>Alumni Prayer Breakfast</h3>
    <p>Warm and inviting design for ILU’s alumni event.</p>
  </div>

  <div class="project">
    <img src="assets/images/isuca-launch.jpg" alt="ISUCA Institute Poster" />
    <h3>ISUCA Institute Launch</h3>
    <p>Green-themed flyer introducing ILU’s sustainability institute.</p>
  </div>

  <div class="project">
    <img src="assets/images/leaders-breakfast.jpg" alt="ILU Leaders Breakfast Poster" />
    <h3>ILU Leaders Breakfast</h3>
    <p>Professional layout for a leadership event featuring Jon Byler.</p>
  </div>

  <div class="project">
    <img src="assets/images/ict-courses.jpg" alt="ICT Courses Poster" />
    <h3>New ICT Courses</h3>
    <p>Tech-forward design promoting ILU’s new certificate programs.</p>
  </div>

  <div class="project">
    <img src="assets/images/labour-day.jpg" alt="Labour Day Poster" />
    <h3>Labour Day Celebration</h3>
    <p>Patriotic design with Kenyan flag elements and a motivational Bible verse.</p>
  </div>

  <div class="project">
    <img src="assets/images/africa-day.jpg" alt="Africa Day Poster" />
    <h3>Africa Day Tribute</h3>
    <p>Vibrant colors and cultural patterns celebrating Africa Day.</p>
  </div>

  <div class="project">
    <img src="assets/images/art-auction.jpg" alt="Art Auction Poster" />
    <h3>Art Auction for a Cause</h3>
    <p>Creative, brush-stroke themed poster inviting artists to submit work.</p>
  </div>

</div>body {
  margin: 0;
  font-family: 'Open Sans', sans-serif;
  background-image: url('assets/images/background.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  color: #fff;
}
body {
  margin: 0;
  font-family: 'Open Sans', sans-serif;
  background-color: #f9f9f9;
  color: #333;
}

header {
  background-color: #1A1A2E;
  color: white;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav h1 {
  font-family: 'Montserrat', sans-serif;
  font-size: 1.5rem;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 1rem;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  text-align: center;
  padding: 4rem 2rem;
  background: linear-gradient(to right, #00BFA6, #FF6B6B);
  color: white;
}

.hero h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.cta-button {
  background-color: white;
  color: #1A1A2E;
  padding: 0.75rem 1.5rem;
  border-radius: 5px;
  text-decoration: none;
  font-weight: bold;
  transition: background-color 0.3s ease;
}

.cta-button:hover {
  background-color: #ddd;
}

footer {
  background-color: #1A1A2E;
  color: white;
  text-align: center;
  padding: 1rem;
  font-size: 0.9rem;
}
.portfolio {
  padding: 2rem;
  text-align: center;
}

.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
  margin-top: 2rem;
}

.project {
  width: 300px;
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  padding: 1rem;
}

.project img {
  width: 100%;
  border-radius: 5px;
}

.project h3 {
  margin-top: 1rem;
  font-size: 1.2rem;
}

.project p {
  font-size: 0.9rem;
  color: #555;
}

.portfolio {
  padding: 2rem;
  text-align: center;
}

.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 2rem;
  margin-top: 2rem;
}

.project {
  width: 300px;
  background-color: white;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  padding: 1rem;
}

.project img {
  width: 100%;
  border-radius: 5px;
}

.project h3 {
  margin-top: 1rem;
  font-size: 1.2rem;
}

.project p {
  font-size: 0.9rem;
  color: #555;
}
