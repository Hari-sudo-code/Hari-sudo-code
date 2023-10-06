<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My E-Commerce Store</title>
    <style>
        /* Your CSS Styles Go Here */
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My E-Commerce Store</h1>
    </Kamalesh>

    <section>
        <h2>Products</h2>
        <div class="product">
            <img src="product1.jpg" alt="Product 1">
            <p>Product 1 Description</p>
            <span>$19.99</span>
            <button>Add to Cart</button>
        </div>

        <div class="product">
            <img src="product2.jpg" alt="Product 2">
            <p>Product 2 Description</p>
            <span>$29.99</span>
            <button>Add to Cart</button>
        </div>

        <!-- Add more product entries as needed -->
    </section>

    <section>
        <h2>Shopping Cart</h2>
        <ul id="cart">
            <!-- Cart items will be dynamically added here using JavaScript -->
        </ul>
        <p>Total: $<span id="total">0.00</span></p>
        <button onclick="checkout()">Checkout</button>
    </section>

    <footer>
        <p>&copy; 2023 My E-Commerce Store</p>
    </footer>

    <script>
        // Your JavaScript Code Goes Here
        function checkout() {
            // Implement checkout functionality
            alert('Thank you for shopping with us!');
        }
    </script>
</body>
</html>
