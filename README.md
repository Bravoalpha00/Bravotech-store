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
        <img src="https://i.ibb.co/YwK0DSQ/acer-predator.jpg" alt="Acer Predator Neo 16">
        <h3>Acer Predator Neo 16 2023</h3>
        <p>I5-13500HX hexacore processor<br>
        RTX4060 8GB dedicated 140W<br>
        16GB DDR5 RAM dual channel<br>
        512GB M.2 SUPER FAST SSD<br>
        16" 165 Hz fast refresh rate screen<br>
        2560 x 1440P (2K) Display<br>
        4 ZONE RGB KEYBOARD<br>
        Original 330W power supply & Packaging<br>
        <strong>Freebies:</strong> Laptop stand & gaming mouse<br>
        <strong>₦1,600,000</strong></p>
        <a href="https://wa.me/+234 805 857 5124?text=Hello%20Bravotech%2C%20I%20want%20to%20buy%20Acer%20Predator%20Neo%2016%202023" target="_blank"><button>Buy Now</button></a>
      </div>
      <div class="card">
        <img src="https://i.ibb.co/KckL3yjV/redmagic-nova-tablet.jpg" alt="Redmagic Nova Tablet">
        <h3>Redmagic Nova Gaming Tablet 16/512GB</h3>
        <p>₦1,100,000</p>
        <a href="https://wa.me/+234 805 857 5124?text=Hello%20Bravotech%2C%20I%20want%20to%20buy%20Redmagic%20Nova%20Gaming%20Tablet%2016%2F512GB" target="_blank"><button>Buy Now</button></a>
      </div>
      <div class="card">
        <img src="https://i.ibb.co/6chHZhT/redmagic-7-pro.jpg" alt="Redmagic 7 Pro">
        <h3>Redmagic 7 Pro 16/256GB</h3>
        <p>₦525,000</p>
        <a href="https://wa.me/+234 805 857 5124?text=Hello%20Bravotech%2C%20I%20want%20to%20buy%20Redmagic%207%20Pro%2016%2F256GB" target="_blank"><button>Buy Now</button></a>
      </div>
      <div class="card">
        <img src="https://i.ibb.co/hxNGkyBt/redmagic.jpg" alt="Redmagic 10 Pro">
        <h3>Redmagic 10 Pro 12/256</h3>
        <p>₦1.15m</p>
        <a href="https://wa.me/+234 805 857 5124?text=Hello%20Bravotech%2C%20I%20want%20to%20buy%20Redmagic%2010%20Pro%2012%2F256" target="_blank"><button>Buy Now</button></a>
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
    <p>WhatsApp: +234 805 857 5124</p>
  </section>  <footer>
    <p>&copy; 2025 Bravotech. All rights reserved.</p>
  </footer>
</body>
</html>
