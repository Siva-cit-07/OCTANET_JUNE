
The Code Is
















<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Lucky Mobile - Affordable Plans</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
    }

    header {
      background: #004aad;
      color: white;
      padding: 15px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    .logo {
      display: flex;
      align-items: center;
    }

    .logo img {
      height: 50px;
      margin-right: 10px;
      border-radius: 5px;
      background: white;
      padding: 5px;
    }

    .logo h1 {
      font-size: 1.5em;
      margin: 0;
    }

    .nav-links {
      display: flex;
      gap: 20px;
    }

    .nav-links a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .nav-links a:hover {
      text-decoration: underline;
    }

    .hero {
      padding: 40px 20px;
      background: #e0f0ff;
      text-align: center;
    }

    .hero h1 {
      margin: 0;
      font-size: 2em;
    }

    .hero p {
      margin: 10px 0;
      color: #555;
    }

    .btn {
      display: inline-block;
      margin-top: 15px;
      padding: 12px 24px;
      background: #007bff;
      color: white;
      text-decoration: none;
      border-radius: 8px;
    }

    .plans {
      padding: 30px 20px;
      display: flex;
      flex-direction: column;
      gap: 20px;
    }

    .plan-card {
      background: white;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    .plan-card h2 {
      margin: 0 0 10px;
    }

    footer {
      background: #004aad;
      color: white;
      text-align: center;
      padding: 15px;
      font-size: 0.9em;
    }

    @media (max-width: 600px) {
      .nav-links {
        flex-direction: column;
        align-items: flex-end;
        margin-top: 10px;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0c/Lucky_Mobile_logo.svg/320px-Lucky_Mobile_logo.svg.png" alt="Lucky Mobile Logo">
      <h1>Lucky Mobile</h1>
    </div>
    <nav class="nav-links">
      <a href="#about">About Us</a>
      <a href="#new">New Arrivals</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Affordable Mobile Plans</h1>
    <p>Starting at just $15/month</p>
    <a class="btn" href="#plans">View Plans</a>
  </section>

  <section class="plans" id="plans">
    <div class="plan-card">
      <h2>$15 Plan</h2>
      <p>Unlimited Canada-wide texting + 100 minutes calling</p>
    </div>
    <div class="plan-card">
      <h2>$25 Plan</h2>
      <p>Unlimited texting + 500 minutes calling + 1GB Data</p>
    </div>
    <div class="plan-card">
      <h2>$40 Plan</h2>
      <p>Unlimited calling & texting + 5GB Data</p>
    </div>
  </section>

  <section id="about" style="padding: 30px 20px;">
    <h2>About Us</h2>
    <p>Lucky Mobile is a budget-friendly carrier with no contracts and reliable nationwide service.</p>
  </section>

  <section id="new" style="padding: 30px 20px; background: #fffbe6;">
    <h2>New Arrivals</h2>
    <p>Check out our latest plans and seasonal offers—limited time only!</p>
  </section>

  <section id="contact" style="padding: 30px 20px;">
    <h2>Contact Us</h2>
    <p>Email: support@luckymobile.ca<br>Phone: 1-888-999-1234</p>
  </section>

  <footer>
    &copy; 2025 Lucky Mobile. All rights reserved.
  </footer>

</body>
</html>

    
     