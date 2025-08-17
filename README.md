<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Your Photography Business</title>
  <style>
    :root {
      --primary: #22223B;
      --accent: #9A8C98;
      --background: #F2E9E4;
      --font: 'Montserrat', Arial, sans-serif;
    }
    body {
      margin: 0;
      font-family: var(--font);
      background: var(--background);
      color: var(--primary);
    }
    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 2rem;
      box-sizing: border-box;
    }
    #logo {
      display: block;
      max-width: 160px;
      margin: 0 auto 2rem;
    }
    h1 {
      text-align: center;
      font-size: 2.6rem;
      color: var(--primary);
      letter-spacing: 2px;
      margin-bottom: 1rem;
    }
    h2 {
      margin-top: 2rem;
      font-size: 1.5rem;
      color: var(--accent);
      text-align: center;
    }
    .about {
      text-align: center;
      margin-bottom: 2rem;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
      margin-bottom: 2rem;
    }
    .gallery img {
      width: 100%;
      height: 170px;
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(34,34,59,.09);
      background: #fff;
      border: 1px solid #eee;
    }
    .contact {
      background: var(--accent);
      color: #fff;
      padding: 1.2rem;
      border-radius: 10px;
      text-align: center;
      margin-bottom: 1rem;
    }
    @media (max-width: 700px) {
      .container { padding: 10px; }
      h1 { font-size: 2rem; }
      .gallery img { height: 120px; }
    }
    @media (max-width: 450px) {
      h1 { font-size: 1.4rem; }
      h2 { font-size: 1.1rem; }
      .gallery img { height: 70px; }
    }
  </style>
</head>
<body>
  <div class="container">
    <img id="logo" src="your-logo.png" alt="Company Logo">
    <h1>Your Photography Business</h1>
    <div class="about">
      <p>Capturing unforgettable moments with artistic expertise.<br>
      Specializing in portraits, events, and nature photography.</p>
    </div>
    <h2>Portfolio Gallery</h2>
    <div class="gallery">
      <img src="photo1.jpg" alt="Sample Portfolio Work">
      <img src="photo2.jpg" alt="Sample Portfolio Work">
      <img src="photo3.jpg" alt="Sample Portfolio Work">
      <!-- Add or remove images easily -->
    </div>
    <h2>Contact</h2>
    <div class="contact">
      <p>Email: <b>youremail@example.com</b><br>
       Phone: <b>+852-1234-5678</b></p>
      <p>
        Find us on 
        <a href="https://instagram.com/" style="color:#fff;text-decoration:underline;" target="_blank">Instagram</a>
        &amp; 
        <a href="https://facebook.com/" style="color:#fff;text-decoration:underline;" target="_blank">Facebook</a>
      </p>
    </div>
  </div>
</body>
</html>
