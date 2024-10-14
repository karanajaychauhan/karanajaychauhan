
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MediStay - Your Trusted Hospital Booking Platform</title>
    <link rel="stylesheet" href="styles.css">
    <!-- You can include Google Fonts or other font libraries here -->
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="logo">
                <h1>MediStay</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Search</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Contact</a></li>
                    <li><a href="#" class="btn-login">Login / Sign Up</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h2>Find and Book the Best Hospitals Near You</h2>
            <form class="search-form">
                <input type="text" placeholder="Enter Location" required>
                <input type="text" placeholder="Specialty (e.g., Cardiology)" required>
                <button type="submit">Search Hospitals</button>
            </form>
        </div>
    </section>

    <!-- Featured Hospitals -->
    <section class="featured">
        <div class="container">
            <h3>Featured Hospitals</h3>
            <div class="hospital-carousel">
                <div class="hospital-card">
                    <img src="hospital1.jpg" alt="Hospital 1">
                    <h4>City Hospital</h4>
                    <p>Cardiology, Neurology, Orthopedics</p>
                    <span class="rating">⭐ 4.5</span>
                    <button>View Details</button>
                </div>
                <div class="hospital-card">
                    <img src="hospital2.jpg" alt="Hospital 2">
                    <h4>Green Valley Medical</h4>
                    <p>General Medicine, Pediatrics, Emergency</p>
                    <span class="rating">⭐ 4.7</span>
                    <button>View Details</button>
                </div>
                <!-- Add more hospital cards as needed -->
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section class="how-it-works">
        <div class="container">
            <h3>How It Works</h3>
            <div class="steps">
                <div class="step">
                    <h4>1. Search</h4>
                    <p>Find hospitals based on your location and medical needs.</p>
                </div>
                <div class="step">
                    <h4>2. Compare</h4>
                    <p>Compare hospitals based on ratings, services, and reviews.</p>
                </div>
                <div class="step">
                    <h4>3. Book</h4>
                    <p>Book appointments or services directly through our platform.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="testimonials">
        <div class="container">
            <h3>What Our Users Say</h3>
            <div class="testimonial-carousel">
                <div class="testimonial">
                    <p>"MediStay made it so easy to find a great hospital for my surgery. Highly recommend!"</p>
                    <span>- John Doe</span>
                </div>
                <div class="testimonial">
                    <p>"Excellent platform with a user-friendly interface. Booking appointments has never been easier."</p>
                    <span>- Jane Smith</span>
                </div>
                <!-- Add more testimonials as needed -->
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-links">
                <a href="#">Privacy Policy</a>
                <a href="#">Terms of Service</a>
                <a href="#">FAQs</a>
            </div>
            <div class="social-media">
                <a href="#">Facebook</a>
                <a href="#">Twitter</a>
                <a href="#">LinkedIn</a>
            </div>
            <p>&copy; 2024 MediStay. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>

/* Reset some basic styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
}

/* Container */
.container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
    overflow: hidden;
}

/* Header */
header {
    background: #2c3e50;
    color: #fff;
    padding: 20px 0;
}

header .logo h1 {
    float: left;
}

header nav {
    float: right;
}

header nav ul {
    list-style: none;
}

header nav ul li {
    display: inline;
    margin-left: 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

.btn-login {
    background: #e74c3c;
    padding: 8px 15px;
    border-radius: 5px;
    transition: background 0.3s;
}

.btn-login:hover {
    background: #c0392b;
}

/* Hero Section */
.hero {
    background: url('hero.jpg') no-repeat center center/cover;
    height: 500px;
    color: #fff;
    display: flex;
    align-items: center;
    text-align: center;
}

.hero h2 {
    font-size: 3em;
    margin-bottom: 20px;
}

.search-form input {
    padding: 10px;
    margin: 5px;
    border: none;
    border-radius: 5px;
    width: 200px;
}

.search-form button {
    padding: 10px 20px;
    border: none;
    background: #e74c3c;
    color: #fff;
    border-radius: 5px;
    cursor: pointer;
    transition: background 0.3s;
}

.search-form button:hover {
    background: #c0392b;
}

/* Featured Hospitals */
.featured {
    padding: 50px 0;
    background: #f4f4f4;
}

.featured h3 {
    text-align: center;
    margin-bottom: 30px;
}

.hospital-carousel {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.hospital-card {
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 10px;
    width: 30%;
    margin-bottom: 20px;
    padding: 15px;
    text-align: center;
    transition: box-shadow 0.3s;
}

.hospital-card:hover {
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.hospital-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
}

.hospital-card h4 {
    margin: 15px 0 10px 0;
}

.hospital-card p {
    color: #777;
    margin-bottom: 10px;
}

.rating {
    color: #f39c12;
    font-weight: bold;
}

.hospital-card button {
    padding: 8px 15px;
    border: none;
    background: #2c3e50;
    color: #fff;
    border-radius: 5px;
    cursor: pointer;
    transition: background 0.3s;
}

.hospital-card button:hover {
    background: #1a252f;
}

/* How It Works */
.how-it-works {
    padding: 50px 0;
}

.how-it-works h3 {
    text-align: center;
    margin-bottom: 30px;
}

.steps {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.step {
    width: 30%;
    text-align: center;
    padding: 20px;
}

.step h4 {
    margin-bottom: 10px;
    color: #e74c3c;
}

.step p {
    color: #555;
}

/* Testimonials */
.testimonials {
    background: #f4f4f4;
    padding: 50px 0;
}

.testimonials h3 {
    text-align: center;
    margin-bottom: 30px;
}

.testimonial-carousel {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.testimonial {
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 10px;
    width: 45%;
    padding: 20px;
    margin-bottom: 20px;
    box-shadow: 0 0 5px rgba(0,0,0,0.1);
}

.testimonial p {
    font-style: italic;
    margin-bottom: 10px;
}

.testimonial span {
    display: block;
    text-align: right;
    color: #333;
}

/* Footer */
footer {
    background: #2c3e50;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

.footer-links a {
    color: #fff;
    margin: 0 10px;
    text-decoration: none;
}

.footer-links a:hover {
    text-decoration: underline;
}

.social-media a {
    color: #fff;
    margin: 0 5px;
    text-decoration: none;
}

.social-media a:hover {
    text-decoration: underline;
}

footer p {
    margin-top: 10px;
    font-size: 0.9em;
}

