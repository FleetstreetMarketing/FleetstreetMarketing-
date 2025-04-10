<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fleetstreet Marketing</title>
  <style>
    body {
      margin: 0;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background: linear-gradient(-45deg, #ff00cc, #3333ff, #00ff99, #ff6600);
      background-size: 400% 400%;
      animation: moveBackground 20s ease infinite;
      color: white;
      overflow-x: hidden;
    }

    @keyframes moveBackground {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .inline-container {
      display: flex;
      flex-wrap: nowrap;
      align-items: center;
      justify-content: space-around;
      padding: 20px;
    }

    .inline-container > * {
      margin: 0 10px;
      text-align: center;
    }

    .logo {
      max-width: 150px;
      height: auto;
    }

    .testimonial, .contact {
      background: rgba(0, 0, 0, 0.6);
      border-radius: 20px;
      padding: 10px;
      box-shadow: 0 0 15px rgba(255, 255, 255, 0.3);
    }

    h1, p {
      margin: 0;
    }

    .testimonial h3 {
      margin-top: 0;
    }
  </style>
</head>
<body>
  <div class="inline-container">
    <img src="/mnt/data/1000000713.png" alt="Fleetstreet Marketing Logo" class="logo">
    <div>
      <h1>Welcome to Fleetstreet Marketing</h1>
      <p>Where creativity drips into reality.</p>
    </div>
    <div class="testimonial">
      <h3>Michael Rogerson</h3>
      <p>"Fleetstreet took my brand to another dimension. Literally mind-blowing work!"</p>
    </div>
    <div class="testimonial">
      <h3>Lu</h3>
      <p>"Working with them was like watching art come to life. Trippy and effective!"</p>
    </div>
    <div class="testimonial">
      <h3>Paris</h3>
      <p>"Fleetstreet’s vision is insane. Colors, vibes, strategy—10/10 experience."</p>
    </div>
    <div class="contact">
      Contact us: 645-223-8691
    </div>
  </div>
</body>
</html>