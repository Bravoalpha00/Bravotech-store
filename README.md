# Bravotech-store
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bravotech Store</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: sans-serif; }
    body { background: #f9f9f9; color: #333; }
    header { background: #0a0a23; color: #fff; padding: 1rem; text-align: center; }
    nav a { color: white; margin: 0 1rem; text-decoration: none; }
    .container { padding: 2rem; }
    .product-grid, .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
      margin-top: 1rem;
    }
    .card {
      background: white;
      border-radius: 10px;
      padding: 1rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: center;
    }
    .card img {
      max-width: 100%;
      border-radius: 8px;
    }
    .card button {
      background-color: #0a0a23;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      margin-top: 0.5rem;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #0a0a23;
      color: white;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bravotech</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#shop">Shop</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>  <section id="home" class="container">
    <h2>Welcome to Bravotech</h2>
    <p>Your one-stop online store for tech gadgets and more!</p>
  </section>  <section id="shop" class="container">
    <h2>Shop</h2>
    <div class="product-grid">
      <div class="card">
        <img src="https://ibb.co/hxNGkyBt" alt="Product 1">
        <h3>Redmagic 10 Pro 12/256</h3>
        <p>₦1.20m</p>
        <a href="https://wa.me/2340000000000?text=Hello%20Bravotech%2C%20I%20want%20to%20buy%20Smart%20Watch" target="_blank"><button>Buy Now</button></a>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/200" alt="Product 2">
        <h3>Wireless Earbuds</h3>
        <p>$30.00</p>
        <a href="https://wa.me/2340000000000?text=Hello%20Bravotech%2C%20I%20want%20to%20buy%20Wireless%20Earbuds" target="_blank"><button>Buy Now</button></a>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/200" alt="Product 3">
        <h3>Bluetooth Speaker</h3>
        <p>$40.00</p>
        <a href="https://wa.me/2340000000000?text=Hello%20Bravotech%2C%20I%20want%20to%20buy%20Bluetooth%20Speaker" target="_blank"><button>Buy Now</button></a>
      </div>
    </div>
  </section>  <section id="gallery" class="container">
    <h2>Gallery</h2>
    <div class="gallery-grid">
      <img src="https://via.placeholder.com/300" alt="Gallery 1" />
      <img src="https://via.placeholder.com/300" alt="Gallery 2" />
      <img src="https://via.placeholder.com/300" alt="Gallery 3" />
    </div>
  </section>  <section id="contact" class="container">
    <h2>Contact Us</h2>
    <p>Email: bravotech@gmail.com</p>
    <p>WhatsApp: +234 000 000 0000</p>
  </section>  <footer>
    <p>&copy; 2025 Bravotech. All rights reserved.</p>
  </footer>
</body>
</html>
