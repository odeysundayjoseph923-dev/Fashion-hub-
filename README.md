<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background-color: #111111;
        color: white;
        text-align: center;
    }

    header {
        background-color: #000000;
        padding: 25px 10px;
    }

    header h1 {
        color: #ffcc00;
        font-size: 32px;
        margin: 0;
    }

    nav {
        background-color: #222222;
        padding: 15px;
    }

    nav a {
        color: white;
        text-decoration: none;
        margin: 10px;
        font-size: 16px;
    }

    .hero {
        padding: 60px 20px;
        background-color: #292929;
    }

    .hero h2 {
        color: #ffcc00;
        font-size: 30px;
    }

    .hero p {
        font-size: 18px;
    }

    .button {
        display: inline-block;
        background-color: #ffcc00;
        color: black;
        padding: 12px 25px;
        text-decoration: none;
        border-radius: 5px;
        font-weight: bold;
        margin-top: 15px;
    }

    .products {
        padding: 30px 15px;
    }

    .product {
        display: inline-block;
        background-color: #222222;
        padding: 20px;
        margin: 10px;
        width: 200px;
        border-radius: 10px;
    }

    .product span {
        font-size: 45px;
    }

    .product h3 {
        color: #ffcc00;
    }

    footer {
        background-color: #000000;
        padding: 20px;
        margin-top: 30px;
    }
</style>
<header>
    <h1>FASHION HUB</h1>
    <p>Your Style, Your Identity!</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
</nav>

<section class="hero" id="home">
    <h2>WELCOME TO FASHION HUB</h2>
    <p>Discover your style. Express yourself.</p>
    <p>Fashion that makes you stand out!</p>
    <a href="#products" class="button">Explore Products</a>
</section>

<section class="products" id="products">
    <h2>OUR COLLECTION</h2>

    <div class="product">
        <span>👕</span>
        <h3>Men's Fashion</h3>
        <p>Discover your perfect look.</p>
    </div>

    <div class="product">
        <span>👗</span>
        <h3>Women's Fashion</h3>
        <p>Style meets elegance.</p>
    </div>

    <div class="product">
        <span>👟</span>
        <h3>Shoes & Sneakers</h3>
        <p>Step out in style.</p>
    </div>

    <div class="product">
        <span>👜</span>
        <h3>Bags & Accessories</h3>
        <p>Complete your look.</p>
    </div>
</section>

<footer id="contact">
    <h2>CONTACT US</h2>
    <p>Thank you for visiting Fashion Hub!</p>
    <p>© 2026 Fashion Hub. All rights reserved.</p>
</footer>
