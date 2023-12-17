# front-end-program
E commerce website front end  using HTML and CSS
<br>
<br>
<h1> HTML portion</h1>
<br>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>E-commerce Website</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>My E-commerce Store</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Products</a></li>
        <li><a href="#">About Us</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="products">
      <div class="product">
        <img src="product1.jpg" alt="Product 1">
        <h2>Product 1</h2>
        <p>Description of Product 1</p>
        <p>$19.99</p>
        <button>Add to Cart</button>
      </div>
      <div class="product">
        <img src="product2.jpg" alt="Product 2">
        <h2>Product 2</h2>
        <p>Description of Product 2</p>
        <p>$24.99</p>
        <button>Add to Cart</button>
      </div>
      <!-- More products can be added similarly -->
    </section>
  </main>

  <footer>
    <p>&copy; 2023 E-commerce Store. All rights reserved.</p>
  </footer>
</body>
</html>
<br>
<h1>CSS portion</h1>
<br>
/* Basic reset and styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
}

header {
  background-color: #f2f2f2;
  padding: 20px;
  text-align: center;
}

nav ul {
  list-style: none;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav ul li a {
  text-decoration: none;
  color: #333;
}

main {
  padding: 20px;
}

.products {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}

.product {
  border: 1px solid #ccc;
  padding: 20px;
  margin-bottom: 20px;
  width: 300px;
  text-align: center;
}

.product img {
  width: 200px;
  height: 200px;
  object-fit: cover;
  margin-bottom: 10px;
}

button {
  padding: 10px 20px;
  background-color: #007bff;
  color: #fff;
  border: none;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #0056b3;
}

footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 10px;
}

