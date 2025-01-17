<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Your Restaurant Name</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Header -->
    <nav class="navbar">
        <div class="logo">
            <a href="#">WHITE chilly</a>
        </div>
        <div class="nav-links" id="navLinks">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#reservation">Reserve</a></li>
            </ul>
        </div>
        <div class="menu-icon" id="menuIcon">
            <span>&#9776;</span> <!-- Hamburger icon -->
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <h2>Welcome to Your Restaurant</h2>
        <p>Where great food and great people meet.</p>
        <button><a href="#reservation">Make a Reservation</a></button>
    </section>

    <!-- Menu Section -->
    <div class="menu-container" id="menu">
        <div class="menu-card">
            <h2 class="menu-title">Our Special Menu</h2>
    
            <div class="menu-category">
                <h3>Starters</h3>
                <ul class="menu-items">
                    <li>
                        <div class="item">
                            <img src="https://b.zmtcdn.com/data/dish_photos/6b0/82fd917a9857895fc722c1a44bca06b0.jpg?output-format=webp" alt="Spring Rolls" class="item-image">
                            <span class="item-name">Spring Rolls</span>
                        </div>
                        <span class="item-price">₹279</span> 
                    </li>
                    <li>
                        <div class="item">
                            <img src="https://b.zmtcdn.com/data/dish_photos/78b/577c536b5e63b3009790619c6ef8f78b.jpg?output-format=webp" alt="Garlic Bread" class="item-image">
                            <span class="item-name">Garlic Bread</span>
                        </div>
                        <span class="item-price">₹359</span> 
                    </li>
                </ul>
            </div>
    
            <div class="menu-category">
                <h3>Main Course</h3>
                <ul class="menu-items">
                    <li>
                        <div class="item">
                            <img src="https://b.zmtcdn.com/data/dish_photos/607/af0e27ae8f20fcdffc3ecbe63e451607.jpeg" alt="Tandoori Panner" class="item-image">
                            <span class="item-name">Tandoori Panner</span>
                        </div>
                        <span class="item-price">₹139</span> 
                    </li>
                    <li>
                        <div class="item">
                            <img src="https://b.zmtcdn.com/data/dish_photos/7e9/db2e3d02d1b36a0229c2298512a467e9.jpeg" alt="Vegetarian Pasta" class="item-image">
                            <span class="item-name">Vegetarian Pasta</span>
                        </div>
                        <span class="item-price">₹339</span> 
                    </li>
                </ul>
            </div>
    
            <div class="menu-category">
                <h3>Desserts</h3>
                <ul class="menu-items">
                    <li>
                        <div class="item">
                            <img src="https://b.zmtcdn.com/data/dish_photos/34b/3950fcb6d76ea750b476bd60234b234b.png?output-format=webp" alt="Chocolate Cake" class="item-image">
                            <span class="item-name">Chocolate Cake</span>
                        </div>
                        <span class="item-price">₹559</span> 
                    </li>
                    <li>
                        <div class="item">
                            <img src="https://b.zmtcdn.com/data/dish_photos/2f6/89d038f3b5a67cb50fa0e9dc8f65f2f6.png?output-format=webp" alt="Apple Pie" class="item-image">
                            <span class="item-name">Apple Pie</span>
                        </div>
                        <span class="item-price">₹399</span> 
                    </li>
                </ul>
            </div>
    
            <div class="menu-category">
                <h3>Beverages</h3>
                <ul class="menu-items">
                    <li>
                        <div class="item">
                            <img src="https://b.zmtcdn.com/data/dish_photos/2f6/89d038f3b5a67cb50fa0e9dc8f65f2f6.png?output-format=webp" alt="Chole Bhature" class="item-image">
                            <span class="item-name">Chole Bhature</span>
                        </div>
                        <span class="item-price">₹279</span> 
                    </li>
                    <li>
                        <div class="item">
                            <img src="https://b.zmtcdn.com/data/dish_photos/07d/d9120fafbc8f6b921ee69a2fc849d07d.jpeg?output-format=webp" alt="Veg Biryani" class="item-image">
                            <span class="item-name">Veg Biryani</span>
                        </div>
                        <span class="item-price">₹239</span> 
                    </li>
                </ul>
            </div>
        </div>
    </div>

    <!-- About Section -->
    <div class="about-container" id="about">
        <section class="about-header">
            <h1>About Us</h1>
            <p>Discover the story behind our restaurant and what makes us special.</p>
        </section>

        <section class="restaurant-history">
            <h2>Our Story</h2>
            <p>Founded in 2010, <strong>WHITE chilly</strong> started as a small neighborhood eatery with a passion for creating bold and unforgettable flavors. Over the years, we’ve evolved into a beloved local spot, renowned for our commitment to fresh ingredients, excellent customer service, and a warm, welcoming atmosphere. Our goal is to provide an exceptional dining experience for every guest who walks through our doors.</p>
        </section>

        <section class="mission-values">
            <h2>Our Mission & Values</h2>
            <div class="values">
                <div class="value-item">
                    <h3>Fresh Ingredients</h3>
                    <p>We source the finest locally grown produce, fresh meats, and hand-picked herbs to ensure every dish bursts with flavor.</p>
                </div>
                <div class="value-item">
                    <h3>Exceptional Service</h3>
                    <p>Our dedicated staff strives to provide a friendly and unforgettable dining experience, making every guest feel at home.</p>
                </div>
                <div class="value-item">
                    <h3>Community Focused</h3>
                    <p>We believe in giving back to the community by supporting local farms and organizing events that bring people together.</p>
                </div>
            </div>
        </section>

    <!-- Reservation Section -->
     <div class="RC" id="reservation">
         <div class="reservation-container">
             <h2>Book Your Table</h2>
             <form action="#" method="POST" class="reservation-form">
     
                 <div class="form-group">
                     <label for="full-name">Full Name</label>
                     <input type="text" id="full-name" name="full_name" required placeholder="Enter your full name">
                 </div>
     
                 <div class="form-group">
                     <label for="email">Email Address</label>
                     <input type="email" id="email" name="email" required placeholder="Enter your email">
                 </div>
     
                 <div class="form-group">
                     <label for="phone">Phone Number</label>
                     <input type="tel" id="phone" name="phone" required placeholder="Enter your phone number">
                 </div>
     
                 <div class="form-group">
                     <label for="reservation-date">Reservation Date</label>
                     <input type="date" id="reservation-date" name="reservation_date" required>
                 </div>
     
                 <div class="form-group">
                     <label for="reservation-time">Reservation Time</label>
                     <input type="time" id="reservation-time" name="reservation_time" required>
                 </div>
     
                 <div class="form-group">
                     <label for="number-of-people">Number of People</label>
                     <input type="number" id="number-of-people" name="number_of_people" required placeholder="How many people?">
                 </div>
     
                 <div class="form-group">
                     <label for="special-request">Special Requests or Notes</label>
                     <textarea id="special-request" name="special_request" rows="4" placeholder="Any special requests?"></textarea>
                 </div>
     
                 <button type="submit" class="submit-btn">Book Reservation</button>
             </form>
         </div>
     </div>

    <!-- Footer -->
    <footer class="footer">
        <div class="footer-container">
            <div class="footer-logo">
                <h3>WHITE chilly</h3>
                <p>&copy; 2025 WHITE chilly. All rights reserved.</p>
            </div>
    
            <div class="footer-nav">
                <h3>Quick Links</h3>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#menu">Menu</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#reservation">Reservations</a></li>
                </ul>
            </div>
    
            <div class="footer-contact">
                <h3>Contact Us</h3>
                <p><strong>Address:</strong> 123 Main Street, City, Country</p>
                <p><strong>Phone:</strong> +1 123 456 7890</p>
                <p><strong>Email:</strong> info@uglyzcafe.com</p>
            </div>
    
            <div class="footer-social">
                <h3>Follow Us</h3>
                <a href="https://facebook.com/" target="_blank">Facebook</a>
                <a href="https://instagram.com/" target="_blank">Instagram</a>
                <a href="https://twitter.com/" target="_blank">Twitter</a>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
    <script>
        // script.js

        const menuIcon = document.getElementById('menuIcon');
        const navLinks = document.getElementById('navLinks');

        // Toggle the navbar visibility when the hamburger icon is clicked
        menuIcon.addEventListener('click', () => {
            navLinks.classList.toggle('active');
        });
    </script>
</body>

</html>
