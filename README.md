<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Wine Pairing Platform</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    /* Reset and base styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    html, body {
      height: 100%;
      font-family: 'Inter', sans-serif;
      color: #fff;
      background: linear-gradient(to bottom, #5b0e2d, #f29ca3); /* Dark red to pink */
    }
    a {
      text-decoration: none;
      color: inherit;
    }

    /* Hero section */
    .hero {
      height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 0 20px;
    }

    .logo {
      max-width: 200px;
      margin-bottom: 30px;
    }

    h1 {
      font-size: 2.5rem;
      font-weight: 800;
      margin-bottom: 20px;
    }

    p {
      font-size: 1.2rem;
      max-width: 600px;
      margin-bottom: 40px;
      line-height: 1.6;
    }

    .btn {
      padding: 12px 30px;
      font-size: 1rem;
      font-weight: 600;
      background: #fff;
      color: #5b0e2d;
      border: 2px solid #fff;
      border-radius: 4px;
      transition: background 0.3s, color 0.3s;
    }

    .btn:hover {
      background: transparent;
      color: #fff;
      border-color: #fff;
    }

    footer {
      position: absolute;
      bottom: 20px;
      width: 100%;
      text-align: center;
      font-size: 0.9rem;
      color: #fff;
      opacity: 0.8;
    }

    /* Hide injected GitHub title if present */
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
    <a class="btn" href="mailto:ddamon0@chicagobooth.edu">Contact Us</a>
  </div>

</body>
</html>
