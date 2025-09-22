<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF‑8">
  <meta name="viewport" content="width=device‑width, initial‑scale=1.0">
  <title>Wine Pairing Platform</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    /* Base resets */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body, html {
      height: 100%;
      font-family: 'Inter', sans-serif;
      color: #222;
    }
    a {
      text-decoration: none;
      color: inherit;
    }

    /* Hero section full screen */
    .hero {
      position: relative;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      text-align: center;
      background: linear-gradient(135deg, #f5f5f5, #e8e8e8);
      /* Or use a background image: background: url('your‑background.jpg') center/cover no-repeat; */
      padding: 0 20px;
    }

    .logo {
      max-width: 200px;
      margin-bottom: 30px;
    }

    .hero h1 {
      font-size: 2.5rem;
      font-weight: 800;
      margin-bottom: 20px;
      color: #333;
    }

    .hero p {
      font-size: 1.2rem;
      color: #555;
      max-width: 600px;
      margin-bottom: 40px;
      line-height: 1.5;
    }

    .buttons {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .btn {
      padding: 12px 30px;
      font-size: 1rem;
      font-weight: 600;
      border: 2px solid #333;
      background: #333;
      color: #fff;
      border-radius: 4px;
      transition: background 0.3s, color 0.3s;
    }
    .btn.outline {
      background: transparent;
      color: #333;
    }
    .btn:hover {
      background: #555;
      color: #fff;
    }
    .btn.outline:hover {
      background: #333;
      color: #fff;
    }

    /* Footer simple */
    footer {
      position: absolute;
      bottom: 20px;
      width: 100%;
      text-align: center;
      font-size: 0.9rem;
      color: #777;
    }

    /* Remove GitHub‑Pages injected title link if still present */
    header h1, header h1 a, .site-title, .repo-name {
      display: none !important;
    }
  </style>
</head>
<body>

  <div class="hero">
    <img class="logo" src="https://github.com/user-attachments/assets/c087912e-b140-4b25-94dc-a204c447c84f" alt="Logo">
    <h1>Coming Soon</h1>
    <p>
      A platform offering seamless, curated wine pairing recommendations to consumers — both at restaurants and at home.
    </p>
    <div class="buttons">
      <!-- Optional buttons -->
      <a class="btn" href="#">Get Started</a>
      <a class="btn outline" href="#">Learn More</a>
    </div>
  </div>

  <footer>
    &copy; 2025 Wine Pairing Platform. All rights reserved.
  </footer>
</body>
</html>
