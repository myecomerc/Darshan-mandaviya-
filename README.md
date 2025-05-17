# Darshan-mandaviya-
/ecommerce-demo
  /index.html
  /login.html
  /styles.css
  /script.js<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Simple E-commerce</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>My E-commerce Store</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="login.html">Login</a>
    </nav>
  </header>

  <main>
    <h2>Products</h2>
    <div class="products">
      <div class="product-card">
        <img src="https://via.placeholder.com/150" alt="Product 1" />
        <h3>Product 1</h3>
        <p>Price: $10</p>
        <button>Add to Cart</button>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/150" alt="Product 2" />
        <h3>Product 2</h3>
        <p>Price: $20</p>
        <button>Add to Cart</button>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/150" alt="Product 3" />
        <h3>Product 3</h3>
        <p>Price: $15</p>
        <button>Add to Cart</button>
      </div>
    </div>
  </main>

  <footer>
    <p>&copy; 2025 My E-commerce Store</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Login - E-commerce</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Login</h1>
    <nav>
      <a href="index.html">Home</a>
    </nav>
  </header>

  <main>
    <form id="loginForm">
      <label for="username">Username:</label><br />
      <input type="text" id="username" name="username" required /><br />

      <label for="password">Password:</label><br />
      <input type="password" id="password" name="password" required /><br />

      <button type="submit">Login</button>
    </form>
    <p id="message"></p>
  </main>

  <footer>
    <p>&copy; 2025 My E-commerce Store</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
