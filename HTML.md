<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>InkIndia - Discover India's Best Tattoo Artists</title>
    <meta name="description" content="Discover India's premier tattoo artists specializing in hand tattoos. Browse portfolios, read reviews, and book consultations with top artists in Mumbai, Delhi, Bangalore & more.">
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <!-- Header -->
    <header class="header">
        <nav class="nav">
            <div class="nav-container">
                <div class="nav-brand">
                    <h2>InkIndia</h2>
                </div>
                <div class="nav-menu">
                    <a href="#home" class="nav-link">Home</a>
                    <a href="#artists" class="nav-link">Artists</a>
                    <a href="#gallery" class="nav-link">Gallery</a>
                    <a href="#studios" class="nav-link">Studios</a>
                    <a href="#reviews" class="nav-link">Reviews</a>
                </div>
                <button class="mobile-menu-btn" id="mobileMenuBtn">
                    <i class="fas fa-bars"></i>
                </button>
            </div>
        </nav>
    </header>

    <!-- Mobile Menu -->
    <div class="mobile-menu" id="mobileMenu">
        <a href="#home" class="mobile-nav-link">Home</a>
        <a href="#artists" class="mobile-nav-link">Artists</a>
        <a href="#gallery" class="mobile-nav-link">Gallery</a>
        <a href="#studios" class="mobile-nav-link">Studios</a>
        <a href="#reviews" class="mobile-nav-link">Reviews</a>
    </div>

    <main>
        <!-- Hero Section -->
        <section id="home" class="hero">
            <div class="hero-content">
                <h1>Discover India's Premier Tattoo Artists</h1>
                <p>Find the perfect artist for your hand tattoo journey. Browse portfolios, read reviews, and book consultations with India's most talented tattoo artists.</p>
                <div class="hero-buttons">
                    <button class="btn btn-primary" onclick="scrollToSection('artists')">Find Artists</button>
                    <button class="btn btn-secondary" onclick="openBookingModal()">Book Consultation</button>
                </div>
            </div>
            <div class="hero-image">
                <img src="https://images.unsplash.com/photo-1598300042247-d088f8ab3a91?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&h=400" alt="Hand Tattoo Art" />
            </div>
        </section>

        <!-- Featured Artists Section -->
        <section id="artists" class="section">
            <div class="container">
                <h2 class="section-title">Featured Artists</h2>
                <div class="artists-grid" id="artistsGrid">
                    <!-- Artists will be populated by JavaScript -->
                </div>
            </div>
        </section>

        <!-- Tattoo Gallery Section -->
        <section id="gallery" class="section gallery-section">
            <div class="container">
                <h2 class="section-title">Hand Tattoo Gallery</h2>
                <div class="gallery-filters">
                    <button class="filter-btn active" data-category="All Designs">All Designs</button>
                    <button class="filter-btn" data-category="Mandala">Mandala</button>
                    <button class="filter-btn" data-category="Minimalist">Minimalist</button>
                    <button class="filter-btn" data-category="Traditional">Traditional</button>
                    <button class="filter-btn" data-category="Geometric">Geometric</button>
                    <button class="filter-btn" data-category="Modern">Modern</button>
                </div>
                <div class="gallery-grid" id="galleryGrid">
                    <!-- Gallery items will be populated by JavaScript -->
                </div>
            </div>
        </section>

        <!-- Studios Section -->
        <section id="studios" class="section">
            <div class="container">
                <h2 class="section-title">Top Studios</h2>
                <div class="studios-grid" id="studiosGrid">
                    <!-- Studios will be populated by JavaScript -->
                </div>
            </div>
        </section>

        <!-- Reviews Section -->
        <section id="reviews" class="section reviews-section">
            <div class="container">
                <h2 class="section-title">Customer Reviews</h2>
                <div class="reviews-grid" id="reviewsGrid">
                    <!-- Reviews will be populated by JavaScript -->
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>InkIndia</h3>
                    <p>India's premier platform for discovering talented tattoo artists and studios.</p>
                </div>
                <div class="footer-section">
                    <h4>Quick Links</h4>
                    <ul>
                        <li><a href="#artists">Artists</a></li>
                        <li><a href="#gallery">Gallery</a></li>
                        <li><a href="#studios">Studios</a></li>
                        <li><a href="#reviews">Reviews</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h4>Contact</h4>
                    <ul>
                        <li><i class="fas fa-envelope"></i> info@inkindia.com</li>
                        <li><i class="fas fa-phone"></i> +91 98765 43210</li>
                        <li><i class="fas fa-map-marker-alt"></i> Mumbai, India</li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 InkIndia. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Booking Modal -->
    <div id="bookingModal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeBookingModal()">&times;</span>
            <h2>Book a Consultation</h2>
            <form id="bookingForm" class="booking-form">
                <div class="form-row">
                    <div class="form-group">
                        <label for="name">Full Name *</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="phone">Phone Number *</label>
                        <input type="tel" id="phone" name="phone" required>
                    </div>
                </div>
                <div class="form-row">
                    <div class="form-group">
                        <label for="email">Email Address *</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="city">City *</label>
                        <select id="city" name="city" required>
                            <option value="">Select City</option>
                            <option value="mumbai">Mumbai</option>
                            <option value="delhi">Delhi</option>
                            <option value="bangalore">Bangalore</option>
                            <option value="kolkata">Kolkata</option>
                            <option value="other">Other</option>
                        </select>
                    </div>
                </div>
                <div class="form-row">
                    <div class="form-group">
                        <label for="designType">Design Type</label>
                        <select id="designType" name="designType">
                            <option value="">Select Design Type</option>
                            <option value="mandala">Mandala</option>
                            <option value="minimalist">Minimalist</option>
                            <option value="traditional">Traditional</option>
                            <option value="geometric">Geometric</option>
                            <option value="custom">Custom Design</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label for="budget">Budget Range</label>
                        <select id="budget" name="budget">
                            <option value="">Select Budget</option>
                            <option value="2500-5000">₹2,500 - ₹5,000</option>
                            <option value="5000-10000">₹5,000 - ₹10,000</option>
                            <option value="10000-15000">₹10,000 - ₹15,000</option>
                            <option value="15000+">₹15,000+</option>
                        </select>
                    </div>
                </div>
                <div class="form-group">
                    <label for="message">Additional Details</label>
                    <textarea id="message" name="message" rows="4" placeholder="Tell us about your tattoo idea, preferred date, or any questions..."></textarea>
                </div>
                <div class="form-actions">
                    <button type="button" class="btn btn-secondary" onclick="closeBookingModal()">Cancel</button>
                    <button type="submit" class="btn btn-primary">Book Consultation</button>
                </div>
            </form>
        </div>
    </div>

    <!-- Artist Profile Modal -->
    <div id="artistModal" class="modal">
        <div class="modal-content modal-large">
            <span class="close" onclick="closeArtistModal()">&times;</span>
            <div id="artistModalContent">
                <!-- Artist profile content will be populated by JavaScript -->
            </div>
        </div>
    </div>

    <!-- Toast Notification -->
    <div id="toast" class="toast">
        <span id="toastMessage"></span>
    </div>

    <script src="script.js"></script>
</body>
</html>


    
