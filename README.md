<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ghee Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Homemade Ghee Store</h1>
            <nav>
                <ul>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#contact">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="hero">
        <div class="container">
            <h2>Pure and Fresh Homemade Ghee</h2>
            <p>Buy the best quality ghee, made with love from fresh milk.</p>
            <a href="#products" class="btn">Shop Now</a>
        </div>
    </section>

    <section id="products" class="container">
        <h2>Our Products</h2>
        <div class="product-list">
            <div class="product-item">
                <img src="ghee-jar.jpg" alt="Ghee Jar">
                <h3>500g Pure Ghee</h3>
                <p>Price: $15</p>
                <button class="btn">Buy Now</button>
            </div>
            <div class="product-item">
                <img src="ghee-jar.jpg" alt="Ghee Jar">
                <h3>1kg Pure Ghee</h3>
                <p>Price: $25</p>
                <button class="btn">Buy Now</button>
            </div>
        </div>
    </section>

    <section id="about" class="container">
        <h2>About Us</h2>
        <p>We produce pure, homemade ghee using traditional methods. Our ghee is made from high-quality milk, ensuring rich flavor and nutrition. We believe in delivering fresh, natural products directly to your home.</p>
    </section>

    <section id="contact" class="container">
        <h2>Contact Us</h2>
        <form action="submit_form.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit" class="btn">Send Message</button>
        </form>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Homemade Ghee Store. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    color: #333;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

header {
    background-color: #FFD700;
    padding: 20px 0;
}

header h1 {
    text-align: center;
    color: #fff;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style-type: none;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

#hero {
    background-image: url('ghee-banner.jpg');
    background-size: cover;
    text-align: center;
    padding: 100px 20px;
}

#hero h2 {
    color: #fff;
    font-size: 2.5em;
}

#hero p {
    color: #fff;
    font-size: 1.2em;
    margin: 10px 0;
}

#hero .btn {
    padding: 10px 20px;
    background-color: #FFD700;
    color: #fff;
    border: none;
    cursor: pointer;
}

#products h2, #about h2, #contact h2 {
    text-align: center;
    margin-bottom: 20px;
}

.product-list {
    display: flex;
    justify-content: space-around;
    margin-bottom: 50px;
}

.product-item {
    text-align: center;
    background-color: #fff;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 8px;
}

.product-item img {
    max-width: 100%;
    height: auto;
}

.product-item h3 {
    margin: 15px 0;
}

.product-item .btn {
    padding: 10px 15px;
    background-color: #FFD700;
    color: #fff;
    border: none;
    cursor: pointer;
}

#contact form {
    display: flex;
    flex-direction: column;
    width: 50%;
    margin: 0 auto;
}

#contact form label {
    margin: 10px 0 5px;
}

#contact form input, #contact form textarea {
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 4px;
}

#contact form .btn {
    margin-top: 10px;
}

footer {
    background-color: #FFD700;
    padding: 10px 0;
    text-align: center;
    color: white;
}
