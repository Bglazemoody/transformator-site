
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Transformator Site</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background: #ffffff;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #333;
      font-weight: 600;
    }
    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 100px 20px;
      text-align: center;
    }
    .hero h1 {
      font-size: 48px;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 20px;
      max-width: 600px;
      margin-bottom: 40px;
    }
    .btn-primary {
      background-color: #1e40af;
      color: #fff;
      padding: 14px 28px;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
    }
    .btn-primary:hover {
      background-color: #1c3faa;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Transformator</div>
    <nav>
      <a href="#about">About</a>
      <a href="#products">Products</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Reliable Transformers</h1>
    <p>High-performance transformers for industrial and commercial use. Efficient, safe, and built to last.</p>
    <button class="btn-primary">Explore Products</button>
  </section>

</body>
</html>
