<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Commercial Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <!-- Navigation Bar -->
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Welcome to our Commercial Website</h1>
        <p>Your one-stop destination for quality products and services.</p>
    </section>

    <section class="products">
        <!-- Product Listings -->
        <!-- This section can be dynamically populated with products using JavaScript or fetched from a backend database with PHP -->
    </section>

    <footer>
        <!-- Footer Section -->
        <p>&copy; 2024 Commercial Website. All rights reserved.</p>
    </footer>
</body>
</html>
CSS Styles (styles.css):
css
Copy code
/* Basic Styling */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    padding: 10px 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background-image: url('hero-image.jpg');
    background-size: cover;
    color: #fff;
    text-align: center;
    padding: 100px 0;
}

.products {
    padding: 50px 0;
}
