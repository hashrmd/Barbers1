# Barbers1
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Premium Barbering | Lordship Lane</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #080808;
      color: #f5f5f5;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    .gold {
      color: #d4af37;
    }

    header {
      position: sticky;
      top: 0;
      z-index: 1000;
      background: #050505;
      border-bottom: 1px solid #d4af37;
      padding: 18px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 24px;
      font-weight: bold;
      color: #d4af37;
      letter-spacing: 1px;
    }

    nav a {
      margin-left: 25px;
      font-size: 15px;
    }

    .btn {
      background: #d4af37;
      color: #080808;
      padding: 12px 22px;
      border-radius: 30px;
      font-weight: bold;
      display: inline-block;
      transition: 0.3s;
    }

    .btn:hover {
      background: #f0cc5c;
      transform: translateY(-2px);
    }

    .hero {
      min-height: 90vh;
      background:
        linear-gradient(rgba(0,0,0,0.65), rgba(0,0,0,0.8)),
        url("https://images.unsplash.com/photo-1621605815971-fbc98d665033?auto=format&fit=crop&w=1600&q=80");
      background-size: cover;
      background-position: center;
      display: flex;
      align-items: center;
      padding: 0 8%;
    }

    .hero-content {
      max-width: 650px;
    }

    .hero h1 {
      font-size: 62px;
      line-height: 1.1;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 20px;
      margin-bottom: 30px;
      color: #ddd;
    }

    section {
      padding: 80px 8%;
    }

    .section-title {
      text-align: center;
      margin-bottom: 50px;
    }

    .section-title h2 {
      font-size: 38px;
      color: #d4af37;
      margin-bottom: 10px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 25px;
    }

    .card {
      background: #111;
      border: 1px solid #2c2c2c;
      padding: 30px;
      border-radius: 16px;
      text-align: center;
      transition: 0.3s;
    }

    .card:hover {
      border-color: #d4af37;
      transform: translateY(-5px);
    }

    .card h3 {
      color: #d4af37;
      margin-bottom: 10px;
    }

    .reviews {
      background: #0d0d0d;
    }

    .review-box {
      max-width: 850px;
      margin: auto;
      overflow: hidden;
      border: 1px solid #d4af37;
      border-radius: 18px;
      padding: 35px;
      text-align: center;
      background: #111;
    }

    .stars {
      color: #d4af37;
      font-size: 24px;
      margin-bottom: 15px;
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 18px;
    }

    .gallery-grid img {
      width: 100%;
      height: 260px;
      object-fit: cover;
      border-radius: 14px;
      border: 1px solid #333;
    }

    .info-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }

    .info-box {
      background: #111;
      padding: 30px;
      border-radius: 16px;
      border: 1px solid #333;
    }

    .info-box h3 {
      color: #d4af37;
      margin-bottom: 15px;
    }

    iframe {
      width: 100%;
      height: 350px;
      border: 0;
      border-radius: 16px;
      margin-top: 25px;
    }

    footer {
      background: #050505;
      border-top: 1px solid #d4af37;
      text-align: center;
      padding: 35px 8%;
      color: #ccc;
    }

    footer .btn {
      margin-top: 20px;
    }

    @media (max-width: 768px) {
      header {
        flex-direction: column;
        gap: 15px;
      }

      nav {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 12px;
      }

      nav a {
        margin-left: 0;
      }

      .hero h1 {
        font-size: 42px;
      }

      .hero p {
        font-size: 17px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">LORDSHIP BARBERS</div>
    <nav>
      <a href="#services">Services</a>
      <a href="#reviews">Reviews</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
      <a href="#booking" class="btn">Book Now</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h1>Premium Barbering in <span class="gold">Lordship Lane</span></h1>
      <p>Sharp cuts, clean fades, beard trims, and classic grooming in London SE22.</p>
      <a href="#booking" class="btn">Book Now</a>
    </div>
  </section>

  <section id="services">
    <div class="section-title">
      <h2>Our Services</h2>
      <p>Modern barbering with classic attention to detail.</p>
    </div>

    <div class="cards">
      <div class="card">
        <h3>Haircuts</h3>
        <p>Clean, sharp cuts tailored to your style.</p>
      </div>
      <div class="card">
        <h3>Skin Fades</h3>
        <p>Fresh fades with a smooth, premium finish.</p>
      </div>
      <div class="card">
        <h3>Beard Trims</h3>
        <p>Shape, line-up, and refine your beard.</p>
      </div>
      <div class="card">
        <h3>Kids Cuts</h3>
        <p>Smart, simple cuts for younger customers.</p>
      </div>
      <div class="card">
        <h3>Styling</h3>
        <p>Finish your look with professional styling.</p>
      </div>
    </div>
  </section>

  <section id="reviews" class="reviews">
    <div class="section-title">
      <h2>What Our Customers Say</h2>
      <p>Google-style customer reviews.</p>
    </div>

    <div class="review-box">
      <div class="stars">★★★★★</div>
      <p id="reviewText">“Great haircut, friendly barbers, and a really clean shop. Highly recommend.”</p>
      <br>
      <strong id="reviewName">— James R.</strong>
    </div>
  </section>

  <section id="gallery">
    <div class="section-title">
      <h2>Gallery</h2>
      <p>Fresh cuts, fades, trims, and shop style.</p>
    </div>

    <div class="gallery-grid">
      <img src="https://images.unsplash.com/photo-1599351431202-1e0f0137899a?auto=format&fit=crop&w=900&q=80" alt="Barber haircut">
      <img src="https://images.unsplash.com/photo-1503951914875-452162b0f3f1?auto=format&fit=crop&w=900&q=80" alt="Barber shop">
      <img src="https://images.unsplash.com/photo-1622287162716-f311baa1a2b8?auto=format&fit=crop&w=900&q=80" alt="Beard trim">
      <img src="https://images.unsplash.com/photo-1621605815971-fbc98d665033?auto=format&fit=crop&w=900&q=80" alt="Modern barber">
    </div>
  </section>

  <section id="contact">
    <div class="section-title">
      <h2>Contact & Location</h2>
      <p>Visit us on Lordship Lane, London.</p>
    </div>

    <div class="info-grid">
      <div class="info-box">
        <h3>Contact</h3>
        <p><strong>Phone:</strong> +44 20 8693 5751</p>
        <p><strong>Address:</strong> 134 Lordship Lane, London, SE22 8HD, England</p>
      </div>

      <div class="info-box">
        <h3>Opening Hours</h3>
        <p>Monday–Friday: 09:00–19:00</p>
        <p>Saturday: 09:00–18:00</p>
        <p>Sunday: 10:00–17:00</p>
      </div>

      <div class="info-box">
        <h3>Payments</h3>
        <p>Accepts Apple Pay</p>
        <p>Accepts contactless payments</p>
      </div>
    </div>

    <iframe
      src="https://www.google.com/maps?q=134%20Lordship%20Lane%20London%20SE22%208HD&output=embed"
      allowfullscreen
      loading="lazy">
    </iframe>
  </section>

  <section id="booking">
    <div class="section-title">
      <h2>Book Your Appointment</h2>
      <p>Ready for your next trim?</p>
      <br>
      <a href="tel:+442086935751" class="btn">Call to Book</a>
    </div>
  </section>

  <footer>
    <p><strong class="gold">LORDSHIP BARBERS</strong></p>
    <p>134 Lordship Lane, London, SE22 8HD</p>
    <p>+44 20 8693 5751</p>
    <a href="tel:+442086935751" class="btn">Book Now</a>
  </footer>

  <script>
    const reviews = [
      {
        text: "“Great haircut, friendly barbers, and a really clean shop. Highly recommend.”",
        name: "— James R."
      },
      {
        text: "“Best fade I’ve had in ages. Quick, professional, and good atmosphere.”",
        name: "— Daniel M."
      },
      {
        text: "“Really good service and easy to pay with contactless. Will definitely come back.”",
        name: "— Alex T."
      }
    ];

    let index = 0;

    setInterval(() => {
      index = (index + 1) % reviews.length;
      document.getElementById("reviewText").textContent = reviews[index].text;
      document.getElementById("reviewName").textContent = reviews[index].name;
    }, 3500);
  </script>

</body>
</html>
