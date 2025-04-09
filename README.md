# sirkewala
Sirkewala – an FMCG brand offering premium quality vinegar, cumin seeds, and whole spices.
# Prepare updated HTML content with correct image paths
updated_html = """<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sirkewala | Pure Spices & Vinegar</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fdfbf7;
    }
    header {
      background-color: #673ab7;
      color: white;
      padding: 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
    }
    nav {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      background: #9575cd;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      padding: 20px;
    }
    h2 {
      text-align: center;
      color: #333;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .card {
      background: white;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
      padding: 15px;
      text-align: center;
    }
    .card img {
      max-width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 8px;
    }
    .buy-btn {
      margin-top: 10px;
      padding: 10px 20px;
      background-color: #4caf50;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
    }
    .buy-btn:hover {
      background-color: #43a047;
    }
    .footer {
      background: #eee;
      padding: 20px;
      text-align: center;
      font-size: 14px;
      color: #555;
    }
    @media (max-width: 600px) {
      .buy-btn {
        display: block;
        width: 100%;
      }
    }
    .whatsapp-btn {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      border: none;
      border-radius: 50%;
      padding: 15px;
      font-size: 24px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      z-index: 100;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Sirkewala</h1>
    <p>Pure Vinegar & Whole Spices – Traditional Taste, Modern Quality</p>
  </header>

  <nav>
    <a href="#products">Products</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">
    <section id="products">
      <h2>Our Products</h2>
      <div class="products">
        <div class="card">
          <img src="images/vinegar.jpeg" alt="Vinegar" />
          <h3>Natural Vinegar</h3>
          <p>Available in Apple Cider, Synthetic, and White variants.</p>
          <a class="buy-btn" href="https://wa.me/919919236519?text=I%20want%20to%20order%20Vinegar%20from%20Sirkewala">Buy Now</a>
        </div>
        <div class="card">
          <img src="images/cumin seed.jpeg" alt="Cumin Seeds" />
          <h3>Cumin Seeds (Jeera)</h3>
          <p>Premium quality, packed with aroma and flavor.</p>
          <a class="buy-btn" href="https://wa.me/919919236519?text=I%20want%20to%20order%20Cumin%20Seeds%20from%20Sirkewala">Buy Now</a>
        </div>
        <div class="card">
          <img src="images/whole spice.jpeg" alt="Whole Spices" />
          <h3>Whole Spices</h3>
          <p>Clove, Cinnamon, Cardamom, and more – handpicked and sun-dried.</p>
          <a class="buy-btn" href="https://wa.me/919919236519?text=I%20want%20to%20order%20Whole%20Spices%20from%20Sirkewala">Buy Now</a>
        </div>
      </div>
    </section>

    <section id="about">
      <h2>About Sirkewala</h2>
      <p>
        Sirkewala is committed to delivering the finest quality of natural vinegar and spices,
        sourced directly from farms and processed with care. We believe in the purity of tradition and
        the trust of our customers.
      </p>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p>Email: contact@sirkewala.in</p>
      <p>Phone: +91-9919236519</p>
      <p>Follow us on Instagram: <a href="https://instagram.com/sirkewala" target="_blank">@sirkewala</a></p>
    </section>
  </div>

  <a class="whatsapp-btn" href="https://wa.me/919919236519" target="_blank">💬</a>

  <div class="footer">
    &copy; 2025 Sirkewala. All rights reserved.
  </div>
</body>
</html>
"""

# Save updated HTML to file
output_html_path = "/mnt/data/sirkewala_updated/index.html"
os.makedirs(os.path.dirname(output_html_path), exist_ok=True)
with open(output_html_path, "w") as f:
    f.write(updated_html)

output_html_path

  

 
