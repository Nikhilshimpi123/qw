# qw
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple E-Commerce Website</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        nav ul {
            list-style: none;
            padding: 10px;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        .products {
            display: flex;
            justify-content: space-around;
            padding: 30px 0;
        }

        .product {
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 250px;
            padding: 20px;
            text-align: center;
            border-radius: 8px;
        }

        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }

        .product h2 {
            margin: 15px 0;
            font-size: 18px;
        }

        .product p {
            font-size: 16px;
            margin: 10px 0;
            font-weight: bold;
        }

        .buy-btn {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
        }

        .buy-btn:hover {
            background-color: #218838;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Simple E-Commerce Store</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">Cart</a></li>
            </ul>
        </nav>
    </header>

    <section class="products">
        <div class="product">
            <img src="product1.jpg" alt="Product 1">
            <h2>Product 1</h2>
            <p>$19.99</p>
            <button class="buy-btn" onclick="alert('Product 1 added to cart!')">Buy Now</button>
        </div>

        <div class="product">
            <img src="product2.jpg" alt="Product 2">
            <h2>Product 2</h2>
            <p>$29.99</p>
            <button class="buy-btn" onclick="alert('Product 2 added to cart!')">Buy Now</button>
        </div>

        <div class="product">
            <img src="product3.jpg" alt="Product 3">
            <h2>Product 3</h2>
            <p>$39.99</p>
            <button class="buy-btn" onclick="alert('Product 3 added to cart!')">Buy Now</button>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Simple E-Commerce Store</p>
    </footer>
</body>
</html>
