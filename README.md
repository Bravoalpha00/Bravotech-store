<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bravotech Store</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #0d1b2a;
      --accent: #00b4d8;
      --text: #ffffff;
      --bg: #1e2a38;
    }body {
  font-family: 'Inter', sans-serif;
  background: var(--bg);
  color: var(--text);
  margin: 0;
  padding: 0;
}

header {
  background: var(--primary);
  padding: 1.5rem;
  text-align: center;
}

header h1 {
  margin: 0;
  font-size: 2rem;
  color: var(--accent);
}

nav {
  margin-top: 0.5rem;
}

nav a {
  color: #ccc;
  margin: 0 1rem;
  text-decoration: none;
}

.container {
  padding: 2rem 1rem;
  max-width: 1200px;
  margin: auto;
}

.search-bar {
  margin-bottom: 2rem;
  text-align: center;
}

.search-bar input {
  padding: 0.7rem;
  width: 80%;
  max-width: 500px;
  border-radius: 8px;
  border: none;
}

.categories {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  justify-content: center;
  margin-bottom: 2rem;
}

.categories button {
  background: var(--accent);
  border: none;
  padding: 0.5rem 1rem;
  color: #000;
  border-radius: 5px;
  cursor: pointer;
}

.product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
}

.card {
  background: var(--primary);
  border-radius: 10px;
  padding: 1rem;
  text-align: center;
  box-shadow: 0 0 10px rgba(0,0,0,0.3);
  transition: transform 0.2s;
}

.card:hover {
  transform: scale(1.02);
}

.card img {
  width: 100%;
  max-height: 200px;
  object-fit: cover;
  border-radius: 8px;
}

.card h3 { margin: 1rem 0 0.5rem; }

.card p { font-size: 0.9rem; color: #ccc; }

.card button {
  background: var(--accent);
  border: none;
  padding: 0.5rem 1rem;
  color: #000;
  border-radius: 5px;
  cursor: pointer;
  margin-top: 1rem;
}

footer {
  text-align: center;
  background: var(--primary);
  padding: 1.5rem;
  margin-top: 4rem;
}

/* Contact form */
.contact-form {
  margin-top: 4rem;
  background: #16212e;
  padding: 2rem;
  border-radius: 8px;
}

.contact-form h2 {
  margin-bottom: 1rem;
}

.contact-form input, .contact-form textarea {
  width: 100%;
  padding: 0.75rem;
  margin: 0.5rem 0;
  border: none;
  border-radius: 6px;
}

.contact-form button {
  background: var(--accent);
  border: none;
  padding: 0.75rem 1.5rem;
  border-radius: 6px;
  cursor: pointer;
  margin-top: 1rem;
}

.testimonials {
  margin: 4rem 0;
  text-align: center;
}

.testimonial {
  background: #111926;
  border-radius: 10px;
  padding: 1rem;
  margin: 1rem auto;
  max-width: 500px;
  font-style: italic;
}

  </style>
</head>
<body>
  <header>
    <h1>Bravotech</h1>
    <nav>
      <a href="#shop">Shop</a>
      <a href="#contact">Contact</a>
      <a href="#admin">Admin</a>
    </nav>
  </header>  <div class="container">
    <div class="search-bar">
      <input type="text" placeholder="Search products..." />
    </div><div class="categories">
  <button>All</button>
  <button>Laptops</button>
  <button>Phones</button>
  <button>Tablets</button>
  <button>Accessories</button>
</div>

<div class="product-grid">
  <!-- Example Product Card -->
  <div class="card">
    <img src="https://i.ibb.co/YwK0DSQ/acer-predator.jpg" alt="Acer Predator" />
    <h3>Acer Predator Neo 16</h3>
    <p>16GB RAM / RTX4060 / ₦1,600,000</p>
    <a href="https://wa.me/2340000000000?text=I want to buy Acer Predator Neo 16"><button>Buy Now</button></a>
  </div>
  <!-- Add more cards dynamically -->
</div>

<div class="testimonials">
  <h2>What Our Customers Say</h2>
  <div class="testimonial">“Super fast delivery and excellent products!”</div>
  <div class="testimonial">“I love the support. Bought a laptop and got a free mouse!”</div>
</div>

<div class="contact-form" id="contact">
  <h2>Contact Us</h2>
  <form>
    <input type="text" placeholder="Your Name" required />
    <input type="email" placeholder="Your Email" required />
    <textarea rows="5" placeholder="Your Message"></textarea>
    <button type="submit">Send Message</button>
  </form>
</div>

  </div>  <footer>
    <p>&copy; 2025 Bravotech. All rights reserved.</p>
  </footer>
</body>
</html>
