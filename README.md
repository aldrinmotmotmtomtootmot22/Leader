# Leader
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Philippine Restaurants Guide</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f9f9f9;
    }

    header {
      background-color: #ff4d4d;
      color: white;
      padding: 20px;
      text-align: center;
    }

    .hero {
      padding: 40px 20px;
      background-color: #ffe6e6;
      text-align: center;
    }

    .hero h1 {
      margin: 0 0 10px;
    }

    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .card {
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      overflow: hidden;
    }

    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .card-content {
      padding: 15px;
    }

    .card-content h3 {
      margin-top: 0;
    }

    footer {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Explore Restaurants in the Philippines</h1>
    <p>Your guide to the best food spots across the islands</p>
  </header>

  <section class="hero">
    <h1>Welcome to Food Pinoy!</h1>
    <p>Discover hidden gems, famous chains, and local favorites from Luzon to Mindanao.</p>
  </section>

  <section class="container">
    <div class="card">
      <img src="https://via.placeholder.com/400x180" alt="Restaurant Photo">
      <div class="card-content">
        <h3>Sample Restaurant Name</h3>
        <p>Short description of the restaurant. Talk about cuisine, price range, and atmosphere.</p>
      </div>
    </div>

  </section>

  <footer>
    &copy; 2025 Food Pinoy. All rights reserved.
  </footer>

</body>
</html>