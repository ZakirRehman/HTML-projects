# HTML-projects An online clothing store
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clothing Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 1rem;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        main {
            padding: 2rem;
        }

        .product-list {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .product {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 1rem;
            padding: 1rem;
            text-align: center;
            width: 30%;
        }

        .product img {
            max-width: 100%;
            height: auto;
        }

        .buy-now {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #28a745;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }

        .buy-now:hover {
            background-color: #218838;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our Clothing Store</h1>
        <nav>
            <ul>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="products">
            <h2>Featured Products</h2>
            <div class="product-list">
                <div class="product">
                    <img src="https://includ.com/cdn/shop/files/active_15_10_202420241015-172021_913e39a9-8588-4d13-8e7b-60d8e853e2c0_1024x1024.jpg?v=1735824098" alt="Product 1">
                    <h3>Kids jeans</h3>
                    <p>Rs 2029.99</p>
                    <a href="#" class="buy-now">Buy Now</a>
                </div>
                <div class="product">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSMk8IiZ69CNBCcIm4CbRP7zbwYBEOoc4F6Pw&s" alt="Product 2">
                    <h3>VELVET SHRUG</h3>
                    <p>Rs 3139.99</p>
                    <a href="#" class="buy-now">Buy Now</a>
                </div>
                <div class="product">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ57A8h2KE-vMCRP9q5WUpOaBaPwHmjob5PXw&s" alt="Product 3">
                    <h3>Kamez Kurtha</h3>
                    <p>Rs 2099</p>
                    <a href="#" class="buy-now">Buy Now</a>
                </div>
            </div>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>We offer a wide range of clothing for all occasions. Our mission is to provide quality apparel at affordable prices.</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>Email: Zakirrehman037@gmail.com</p>
            <p>Phone: 3170846128</p>
        </section>
        <section id="Feedback">
            <h1>Feedback</h1>
            <textarea name="feeback" id="101" placeholder="Provide us our Feedback" rows="1"></textarea>

        </section>
    </main>
 <br/>
 <br/><br/><br/><br/><br/>
    <footer>
        <p>&copy; 2023 Clothing Store. All rights reserved.</p>
    </footer>
</body>
</html>
