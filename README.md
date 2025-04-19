<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Libera Tour India</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #d6f0f7, #ffffff);
      color: #333;
    }

    header {
      background: #0077b6;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3.5rem;
      margin: 0;
      font-weight: bold;
      letter-spacing: 2px;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.3);
    }

    nav {
      background: #023e8a;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e') center/cover no-repeat;
      color: white;
      padding: 100px 20px;
      text-align: center;
    }

    .hero h2 {
      font-size: 2.5rem;
      margin: 0;
    }

    .cta-btn {
      background-color: #023e8a;
      color: white;
      padding: 15px 30px;
      border-radius: 5px;
      font-size: 1.2rem;
      text-decoration: none;
      transition: background-color 0.3s ease;
    }

    .cta-btn:hover {
      background-color: #0077b6;
    }

    .section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
      text-align: center;
    }

    /* Style for highlighted section titles */
    #about-us h2,
    #travel-experience h2,
    #why-travel-with-us h2,
    #wildlife h2,
    #culture h2,
    #booking h2,
    #gallery h2 {
      font-size: 3rem;
      color: #023e8a;
    }

    footer {
      background: #0077b6;
      color: white;
      padding: 20px;
      text-align: center;
    }

    footer a {
      color: white;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .gallery-item img {
      width: 100%;
      height: auto;
      border-radius: 8px;
    }

    @media only screen and (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
      .hero h2 {
        font-size: 1.8rem;
      }
      nav {
        text-align: left;
      }
      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about-us">About Us</a>
    <a href="#travel-experience">Travel Experience</a>
    <a href="#wildlife">Wildlife</a>
    <a href="#culture">Culture & Heritage</a>
    <a href="#gallery">Gallery</a>
    <a href="#booking">Booking</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Header Section -->
  <header>
    <h1>Libera Tours</h1>
  </header>

  <!-- Hero Section -->
  <section class="hero" id="home">
    <h2>Explore India with Passion & Purpose</h2>
    <p>Discover the majestic beauty of India through personalized tours</p>
    <a href="#booking" class="cta-btn">Book Your Adventure</a>
  </section>

  <!-- About Us Section -->
  <section class="section" id="about-us">
    <h2>About Us</h2>
    <p>Libera Tour India is a premier travel agency dedicated to showcasing the heart and soul of India. We curate personalized tours that reflect India’s incredible diversity, from bustling cities and ancient temples to serene backwaters and lush jungles.</p>
    <p>Our team of local experts ensures every detail of your journey is tailored to your interests, providing safe, seamless, and unforgettable experiences.</p>
  </section>

  <!-- Travel Experience Section -->
  <section class="section" id="travel-experience">
    <h2>Travel Experience</h2>
    <p>With over a decade of experience, Libera Tour India crafts unforgettable travel moments. We offer heritage walks, jungle safaris, cultural deep-dives, and more. Join thousands of travelers who have explored India’s wonders with us.</p>
  </section>

  <!-- Wildlife Section -->
  <section class="section" id="wildlife">
    <h2>Wildlife Tours</h2>
    <p>India's wildlife sanctuaries are home to majestic tigers, elephants, rhinos, and countless bird species. Our wildlife tours include jeep safaris in Ranthambore, Kaziranga, and Jim Corbett, and nature walks through lesser-known reserves. With our expert naturalists, you’ll gain insights into India’s rich biodiversity.</p>
  </section>

  <!-- Culture & Heritage Section -->
  <section class="section" id="culture">
    <h2>Cultural Heritage</h2>
    <p>India's cultural heritage spans thousands of years. Explore UNESCO World Heritage sites, ancient temples, royal palaces, vibrant festivals, and traditional arts and crafts. From Varanasi’s ghats to Rajasthan’s forts, immerse yourself in the traditions that define India’s identity.</p>
  </section>

  <!-- Gallery Section -->
  <section class="section" id="gallery">
    <h2>Gallery</h2>
    <p>Explore our collection of stunning images from across India. From desert dunes to tropical coastlines, spiritual sites to wildlife safaris, these moments capture the magic of traveling with Libera Tour India.</p>
    <div class="gallery">
      <div class="gallery-item">
        <img src="https://via.placeholder.com/400" alt="Gallery Image 1">
      </div>
      <div class="gallery-item">
        <img src="https://via.placeholder.com/400" alt="Gallery Image 2">
      </div>
      <div class="gallery-item">
        <img src="https://via.placeholder.com/400" alt="Gallery Image 3">
      </div>
    </div>
  </section>

  <!-- Booking Section -->
  <section class="section" id="booking">
    <h2>Book Your Trip</h2>
    <form action="mailto:liberatours@gmail.com" method="post" enctype="text/plain">
      <label>Name:<br><input type="text" name="name" required></label><br><br>
      <label>Email:<br><input type="email" name="email" required></label><br><br>
      <label>Destination:<br><input type="text" name="destination"></label><br><br>
      <label>Message:<br><textarea name="message"></textarea></label><br><br>
      <button type="submit">Submit Booking</button>
    </form>
  </section>

  <!-- Contact Section -->
  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p>📞 Call us: <a href="tel:+919818251206">+91 9818251206</a> | 📧 Email: 
      <a href="mailto:liberatours@gmail.com">liberatours@gmail.com</a>, 
      <a href="mailto:veeruindia@gmail.com">veeruindia@gmail.com</a>
    </p>
    <p>Follow us on social media for the latest updates and travel inspiration.</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Libera Tour India. All rights reserved.</p>
  </footer>

</body>
</html>
