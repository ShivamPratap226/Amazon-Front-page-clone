<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon Clone</title>

    <!-- Font Awesome for cart and icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    
    <!-- Linking our CSS file -->
    <link rel="stylesheet" href="Amazon.css">
</head>
<body>

    <!-- Main navbar section -->
    <header>
        <div class="navbar">
            
            <!-- Amazon logo -->
            <div class="nav-logo">
                <div class="logo"></div>
            </div>

            <!-- Delivery section -->
            <div class="nav-address">
                <p class="small-text">Deliver to</p>
                <div class="location">
                    <i class="fa-solid fa-location-dot"></i>
                    <p>India</p>
                </div>
            </div>

            <!-- Search box -->
            <div class="nav-search">
                <select>
                    <option>All</option>
                </select>
                <input type="text" placeholder="Search Amazon">
                <button><i class="fa-solid fa-magnifying-glass"></i></button>
            </div>

            <!-- Sign-in section -->
            <div class="nav-signin">
                <p>Hello, Sign in</p>
                <p><strong>Account & Lists</strong></p>
            </div>

            <!-- Returns & Orders  -->
            <div class="nav-orders">
                <p>Returns</p>
                <p><strong>& Orders</strong></p>
            </div>

            <!-- Cart icon -->
            <div class="nav-cart">
                <i class="fa-solid fa-cart-shopping"></i>
                <p>Cart</p>
            </div>
        </div>

        <!-- Small menu under navbar -->
        <div class="panel">
            <p><i class="fa-solid fa-bars"></i> All</p>
            <p>Today's Deals</p>
            <p>Customer Service</p>
            <p>Gift Cards</p>
            <p>Sell</p>
        </div>
    </header>

    <!-- Banner or Hero image -->
    <div class="hero">
        <div class="hero-msg">
            <p>You're on Amazon.com. You can also shop on Amazon India for local products. <a href="#">Click here</a></p>
        </div>
    </div>

    <!-- Product boxes section -->
    <div class="products">
        <!-- 1st box -->
        <div class="box">
            <h2>Clothing</h2>
            <div class="box-img" style="background-image: url('https://m.media-amazon.com/images/I/61Wvx3UZzXL._SX3000_.jpg');"></div>
            <a href="#">Shop now</a>
        </div>

        <!-- 2nd box -->
        <div class="box">
            <h2>Electronics</h2>
            <div class="box-img" style="background-image: url('https://m.media-amazon.com/images/I/71RdoeT+X4L._SX679_.jpg');"></div>
            <a href="#">See more</a>
        </div>

        <!-- 3rd box -->
        <div class="box">
            <h2>Home Appliances</h2>
            <div class="box-img" style="background-image: url('https://m.media-amazon.com/images/I/71bZ9rHAXjL._SX679_.jpg');"></div>
            <a href="#">Explore</a>
        </div>

        <!-- 4th box -->
        <div class="box">
            <h2>Beauty Products</h2>
            <div class="box-img" style="background-image: url('https://m.media-amazon.com/images/I/71gB9vFey-L._SX679_.jpg');"></div>
            <a href="#">Check deals</a>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <div class="footer-back">
            <p>Back to top</p>
        </div>
        <div class="footer-bottom">
            <p>© 2027 Amazon by Shivam Pratap Singh😎</p>
        </div>
    </footer>

</body>
</html>
