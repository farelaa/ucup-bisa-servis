<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Ucup's Phone Repair Shop - Professional Phone Repair</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap');

  * {
    box-sizing: border-box;
    margin: 0; padding: 0;
  }

  body {
    font-family: 'Poppins', sans-serif;
    background: #f2f7fa;
    color: #333;
    line-height: 1.6;
  }

  header {
    background: #004aad;
    color: #fff;
    padding: 2rem 1rem;
    text-align: center;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  }

  header h1 {
    font-weight: 700;
    font-size: 2.5rem;
    letter-spacing: 2px;
    margin-bottom: 0.2rem;
  }

  header p {
    font-weight: 300;
    font-size: 1.2rem;
    opacity: 0.9;
  }

  nav {
    margin-top: 1rem;
  }

  nav a {
    color: #bbdefb;
    margin: 0 1rem;
    text-decoration: none;
    font-weight: 500;
    transition: color 0.3s ease;
  }

  nav a:hover {
    color: #fff;
  }

  main {
    max-width: 1000px;
    margin: 2rem auto;
    padding: 0 1rem;
  }

  section {
    margin-bottom: 3rem;
    background: #fff;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,74,173,0.1);
  }

  h2 {
    color: #004aad;
    margin-bottom: 1rem;
    font-weight: 700;
    font-size: 2rem;
    border-bottom: 3px solid #004aad;
    display: inline-block;
    padding-bottom: 0.3rem;
  }

  p {
    font-weight: 400;
    font-size: 1rem;
    margin-bottom: 1rem;
    color: #555;
  }

  ul.services-list {
    list-style: none;
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
    gap: 1.5rem;
  }

  ul.services-list li {
    background: #eaf2ff;
    padding: 1.5rem;
    border-radius: 8px;
    box-shadow: inset 0 0 10px #c8dafc;
    transition: background 0.3s ease;
    text-align: center;
  }

  ul.services-list li:hover {
    background: #bbdefb;
    cursor: default;
  }

  ul.services-list li h3 {
    color: #004aad;
    margin-bottom: 0.6rem;
    font-weight: 600;
  }

  #contact {
    text-align: center;
  }

  #contact p {
    font-size: 1.1rem;
    margin-bottom: 1rem;
  }

  .btn-primary {
    display: inline-block;
    background: #004aad;
    color: #fff;
    padding: 0.8rem 2rem;
    font-weight: 600;
    font-size: 1.1rem;
    border-radius: 40px;
    text-decoration: none;
    box-shadow: 0 5px 15px rgba(0,74,173,0.3);
    transition: background 0.3s ease;
  }

  .btn-primary:hover {
    background: #003580;
  }

  footer {
    background: #002e6b;
    color: #ccc;
    text-align: center;
    padding: 1rem 1rem;
    font-size: 0.9rem;
    margin-top: 3rem;
  }

  /* Responsive */
  @media (max-width: 600px) {
    header h1 {
      font-size: 2rem;
    }

    nav a {
      margin: 0 0.5rem;
      font-size: 0.9rem;
    }

    ul.services-list {
      grid-template-columns: 1fr;
    }

    main {
      margin: 1rem;
    }
  }
</style>
</head>
<body>
<header>
  <h1>Ucup's Phone Repair Shop</h1>
  <p>Professional & Trusted Phone Repair in Your Area</p>
  <nav>
    <a href="#about">About Us</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact Us</a>
  </nav>
</header>

<main>
  <section id="about">
    <h2>About Us</h2>
    <p>Welcome to <strong>Ucup's Phone Repair Shop</strong>, your trusted and experienced place for fixing all phone problems. With expert technicians and quality parts, we ensure your phone is restored like new.</p>
    <p>We serve all brands and phone types with affordable prices and fast service.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul class="services-list">
      <li>
        <h3>Screen Replacement</h3>
        <p>Replacement of cracked or broken screens with high-quality original parts.</p>
      </li>
      <li>
        <h3>Battery Service</h3>
        <p>Fast and safe battery replacement to keep your phone lasting longer.</p>
      </li>
      <li>
        <h3>Software Repair</h3>
        <p>Fix system issues, OS updates, and reinstall without losing data.</p>
      </li>
      <li>
        <h3>Hardware Repair</h3>
        <p>Repair internal components like speakers, microphones, buttons, and more.</p>
      </li>
      <li>
        <h3>Camera Service</h3>
        <p>Repair front and rear cameras to restore clear photo quality.</p>
      </li>
      <li>
        <h3>Free Consultation</h3>
        <p>Free consultation for initial diagnostics and repair cost estimation.</p>
      </li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>It's time to get your phone repaired by the experts! Don't hesitate to contact us now.</p>
    <a href="tel:+6281234567890" class="btn-primary">Call Us</a>
    <p style="margin-top: 1rem;">Or visit our shop at:<br /><strong>Jl. Contoh No. 45, Your City</strong></p>
  </section>
</main>

<footer>
  &copy; 2024 Ucup's Phone Repair Shop | All rights reserved.
</footer>
</body>
</html>


