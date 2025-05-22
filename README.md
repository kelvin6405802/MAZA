# MAZA
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MAZAMW - Premium Music & Movies</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <header>
        <div class="logo-container">
            <h1 class="logo">MAZAMW</h1>
            <p>Premium Entertainment</p>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#movies">Movies</a></li>
                <li><a href="#music">Music</a></li>
                <li><a href="#subscription">Subscription</a></li>
                <li><a href="#about">About</a></li>
            </ul>
        </nav>
        <div class="auth-buttons">
            <button class="login-btn">Login</button>
            <button class="signup-btn">Sign Up</button>
        </div>
    </header>

    <main>
        <section id="hero" class="hero-section">
            <div class="hero-content">
                <h2>Unlimited Entertainment</h2>
                <p>Stream the latest movies and music anywhere, anytime</p>
                <button class="cta-btn">Start Your Free Trial</button>
            </div>
        </section>

        <section id="featured" class="featured-section">
            <h2>Featured Content</h2>
            <div class="content-grid">
                <div class="content-card">
                    <img src="https://via.placeholder.com/300x450" alt="Movie Poster">
                    <h3>Blockbuster Movie</h3>
                    <p>Action • 2023</p>
                </div>
                <div class="content-card">
                    <img src="https://via.placeholder.com/300x450" alt="Album Cover">
                    <h3>Top Hits Album</h3>
                    <p>Pop • 2023</p>
                </div>
                <div class="content-card">
                    <img src="https://via.placeholder.com/300x450" alt="Movie Poster">
                    <h3>New Release</h3>
                    <p>Comedy • 2023</p>
                </div>
                <div class="content-card">
                    <img src="https://via.placeholder.com/300x450" alt="Album Cover">
                    <h3>Chart Toppers</h3>
                    <p>Various Artists</p>
                </div>
            </div>
        </section>

        <section id="subscription" class="subscription-section">
            <h2>Choose Your Plan</h2>
            <div class="plans-container">
                <div class="plan-card">
                    <h3>Basic</h3>
                    <p class="price">$9.99<span>/month</span></p>
                    <ul>
                        <li>SD Quality</li>
                        <li>1 Device</li>
                        <li>Limited Content</li>
                    </ul>
                    <button class="plan-btn">Select</button>
                </div>
                <div class="plan-card popular">
                    <div class="popular-badge">Most Popular</div>
                    <h3>Standard</h3>
                    <p class="price">$14.99<span>/month</span></p>
                    <ul>
                        <li>HD Quality</li>
                        <li>2 Devices</li>
                        <li>Full Content Library</li>
                    </ul>
                    <button class="plan-btn">Select</button>
                </div>
                <div class="plan-card">
                    <h3>Premium</h3>
                    <p class="price">$19.99<span>/month</span></p>
                    <ul>
                        <li>4K Ultra HD</li>
                        <li>4 Devices</li>
                        <li>Full Content Library</li>
                        <li>Offline Downloads</li>
                    </ul>
                    <button class="plan-btn">Select</button>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="footer-content">
            <div class="footer-section">
                <h3>MAZAMW</h3>
                <p>Your premium destination for music and movies</p>
            </div>
            <div class="footer-section">
                <h4>Quick Links</h4>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">Music</a></li>
                    <li><a href="#">Subscription</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h4>Legal</h4>
                <ul>
                    <li><a href="#">Terms of Service</a></li>
                    <li><a href="#">Privacy Policy</a></li>
                    <li><a href="#">Cookie Policy</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h4>Connect With Us</h4>
                <div class="social-icons">
                    <a href="#"><i class="fab fa-facebook"></i></a>
                    <a href="#"><i class="fab fa-twitter"></i></a>
                    <a href="#"><i class="fab fa-instagram"></i></a>
                    <a href="#"><i class="fab fa-youtube"></i></a>
                </div>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2023 MAZAMW. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background-color: #0f0f1a;
    color: #ffffff;
    line-height: 1.6;
}

/* Header Styles */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 5%;
    background-color: #1a1a2e;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}

.logo-container {
    display: flex;
    align-items: center;
}

.logo {
    font-size: 2rem;
    font-weight: 700;
    color: #e94560;
    margin-right: 0.5rem;
}

.logo-container p {
    font-size: 0.8rem;
    opacity: 0.7;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin: 0 1rem;
}

nav ul li a {
    text-decoration: none;
    color: #ffffff;
    font-weight: 500;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #e94560;
}

.auth-buttons button {
    padding: 0.5rem 1.5rem;
    margin-left: 1rem;
    border: none;
    border-radius: 5px;
    font-weight: 600;
    cursor: pointer;
    transition: all 0.3s;
}

.login-btn {
    background: transparent;
    color: #ffffff;
    border: 1px solid #ffffff;
}

.login-btn:hover {
    background: rgba(255, 255, 255, 0.1);
}

.signup-btn {
    background: #e94560;
    color: #ffffff;
}

.signup-btn:hover {
    background: #d13354;
}

/* Hero Section */
.hero-section {
    height: 100vh;
    background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), 
                url('https://via.placeholder.com/1920x1080') no-repeat center center/cover;
    display: flex;
    align-items: center;
    padding: 0 5%;
    margin-top: 80px;
}

.hero-content {
    max-width: 600px;
}

.hero-content h2 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero-content p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
    opacity: 0.9;
}

.cta-btn {
    padding: 1rem 2.5rem;
    background: #e94560;
    color: #ffffff;
    border: none;
    border-radius: 5px;
    font-size: 1.1rem;
    font-weight: 600;
    cursor: pointer;
    transition: all 0.3s;
}

.cta-btn:hover {
    background: #d13354;
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

/* Featured Section */
.featured-section {
    padding: 5rem 5%;
}

.featured-section h2 {
    font-size: 2.5rem;
    margin-bottom: 2rem;
    text-align: center;
}

.content-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 2rem;
}

.content-card {
    background: #1a1a2e;
    border-radius: 10px;
    overflow: hidden;
    transition: transform 0.3s;
}

.content-card:hover {
    transform: translateY(-10px);
}

.content-card img {
    width: 100%;
    height: auto;
    display: block;
}

.content-card h3 {
    padding: 1rem 1rem 0.5rem;
    font-size: 1.2rem;
}

.content-card p {
    padding: 0 1rem 1rem;
    opacity: 0.7;
    font-size: 0.9rem;
}

/* Subscription Section */
.subscription-section {
    padding: 5rem 5%;
    background: #1a1a2e;
}

.subscription-section h2 {
    font-size: 2.5rem;
    margin-bottom: 2rem;
    text-align: center;
}

.plans-container {
    display: flex;
    justify-content: center;
    gap: 2rem;
    flex-wrap: wrap;
}

.plan-card {
    background: #0f0f1a;
    border-radius: 10px;
    padding: 2rem;
    width: 300px;
    position: relative;
    transition: all 0.3s;
}

.plan-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
}

.plan-card.popular {
    border: 2px solid #e94560;
}

.popular-badge {
    position: absolute;
    top: -15px;
    right: 20px;
    background: #e94560;
    color: white;
    padding: 0.3rem 1rem;
    border-radius: 20px;
    font-size: 0.8rem;
    font-weight: 600;
}

.plan-card h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
}

.price {
    font-size: 2.5rem;
    font-weight: 700;
    margin-bottom: 1.5rem;
    color: #e94560;
}

.price span {
    font-size: 1rem;
    color: #ffffff;
    opacity: 0.7;
}

.plan-card ul {
    list-style: none;
    margin-bottom: 2rem;
}

.plan-card ul li {
    margin-bottom: 0.8rem;
    position: relative;
    padding-left: 1.5rem;
}

.plan-card ul li:before {
    content: "✓";
    color: #e94560;
    position: absolute;
    left: 0;
}

.plan-btn {
    width: 100%;
    padding: 1rem;
    background: #e94560;
    color: white;
    border: none;
    border-radius: 5px;
    font-weight: 600;
    cursor: pointer;
    transition: all 0.3s;
}

.plan-btn:hover {
    background: #d13354;
}

/* Footer Styles */
footer {
    background: #0a0a12;
    padding: 3rem 5% 1rem;
}

.footer-content {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 2rem;
    margin-bottom: 2rem;
}

.footer-section h3, .footer-section h4 {
    color: #e94560;
    margin-bottom: 1rem;
    font-size: 1.2rem;
}

.footer-section p {
    opacity: 0.7;
    margin-bottom: 1rem;
}

.footer-section ul {
    list-style: none;
}

.footer-section ul li {
    margin-bottom: 0.5rem;
}

.footer-section ul li a {
    color: #ffffff;
    text-decoration: none;
    opacity: 0.7;
    transition: opacity 0.3s;
}

.footer-section ul li a:hover {
    opacity: 1;
}

.social-icons {
    display: flex;
    gap: 1rem;
}

.social-icons a {
    color: #ffffff;
    font-size: 1.5rem;
    opacity: 0.7;
    transition: all 0.3s;
}

.social-icons a:hover {
    opacity: 1;
    color: #e94560;
}

.footer-bottom {
    text-align: center;
    padding-top: 1.5rem;
    border-top: 1px solid rgba(255, 255, 255, 0.1);
    opacity: 0.7;
    font-size: 0.9rem;
}

/* Responsive Design */
@media (max-width: 768px) {
    header {
        flex-direction: column;
        padding: 1rem;
        position: relative;
    }

    nav ul {
        margin: 1rem 0;
    }

    .auth-buttons {
        margin-top: 1rem;
    }

    .hero-content h2 {
        font-size: 2rem;
    }

    .plans-container {
        flex-direction: column;
        align-items: center;
    }

    .plan-card {
        width: 100%;
        max-width: 350px;
    }
}
// Basic functionality for the website
document.addEventListener('DOMContentLoaded', function() {
    // Smooth scrolling for navigation links
    document.querySelectorAll('nav a').forEach(anchor => {
        anchor.addEventListener('click', function(e) {
            e.preventDefault();
            
            const targetId = this.getAttribute('href');
            const targetElement = document.querySelector(targetId);
            
            window.scrollTo({
                top: targetElement.offsetTop - 80,
                behavior: 'smooth'
            });
        });
    });

    // Login/Signup button functionality (placeholder)
    const loginBtn = document.querySelector('.login-btn');
    const signupBtn = document.querySelector('.signup-btn');
    
    loginBtn.addEventListener('click', function() {
        alert('Login functionality will be implemented soon!');
    });
    
    signupBtn.addEventListener('click', function() {
        alert('Signup functionality will be implemented soon!');
    });

    // Plan selection functionality
    const planButtons = document.querySelectorAll('.plan-btn');
    
    planButtons.forEach(button => {
        button.addEventListener('click', function() {
            const planName = this.closest('.plan-card').querySelector('h3').textContent;
            alert(`You selected the ${planName} plan. Payment gateway will be implemented soon!`);
        });
    });

    // CTA button functionality
    const ctaBtn = document.querySelector('.cta-btn');
    
    ctaBtn.addEventListener('click', function() {
        alert('Free trial signup will be implemented soon!');
    });
});
