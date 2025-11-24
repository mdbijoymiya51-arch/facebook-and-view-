<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Facebook Like and View</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0; 
    padding: 0; 
    background: linear-gradient(135deg, #f6d365, #fda085, #a1c4fd, #c2e9fb);
    background-size: 400% 400%;
    animation: gradientBG 15s ease infinite;
  }
  @keyframes gradientBG {
    0%{background-position:0% 50%;}
    50%{background-position:100% 50%;}
    100%{background-position:0% 50%;}
  }
  header {
    background-color: #4267B2;
    color: white;
    padding: 20px 0;
    text-align: center;
  }
  nav a {
    margin: 0 15px;
    color: white;
    text-decoration: none;
    font-weight: bold;
  }
  section {
    padding: 50px;
    text-align: center;
  }
  .services {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
  }
  .service-card {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    width: 250px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
  }
  footer {
    background-color: #4267B2;
    color: white;
    text-align: center;
    padding: 20px 0;
  }
  input, textarea {
    width: 80%;
    padding: 10px;
    margin: 10px 0;
    border-radius: 5px;
    border: 1px solid #ccc;
  }
  button {
    padding: 10px 20px;
    background-color: #f39c12;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }
  button:hover {
    background-color: #d35400;
  }
  .social-icons a {
    margin: 0 10px;
    color: white;
    text-decoration: none;
    font-size: 20px;
  }
</style>
</head>
<body>

<header>
  <h1>Facebook Like and View</h1>
  <nav>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="services">
  <h2>Our Services</h2>
  <div class="services">
    <div class="service-card">
      <h3>Facebook Like</h3>
      <p>Grow your Facebook posts with our professional like service.</p>
    </div>
    <div class="service-card">
      <h3>Facebook View</h3>
      <p>Boost your video views to increase reach and engagement.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <form>
    <input type="text" placeholder="Your Name" required><br>
    <input type="email" placeholder="Your Email" required><br>
    <textarea placeholder="Your Message" rows="5" required></textarea><br>
    <button type="submit">Send Message</button>
  </form>
</section>

<footer>
  <p>Follow us on:</p>
  <div class="social-icons">
    <a href="https://www.facebook.com/" target="_blank">Facebook</a>
  </div>
  <p>&copy; 2025 Facebook Like and View</p>
</footer>

</body>
</html>
