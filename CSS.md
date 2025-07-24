/* Reset and Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Inter', sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #fafafa;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Header */
.header {
    background: #1a1a1a;
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 1000;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.nav {
    padding: 1rem 0;
}

.nav-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.nav-brand h2 {
    color: #d4af37;
    font-weight: 700;
    font-size: 1.8rem;
}

.nav-menu {
    display: flex;
    gap: 2rem;
}

.nav-link {
    color: #fff;
    text-decoration: none;
    font-weight: 500;
    transition: color 0.3s ease;
}

.nav-link:hover {
    color: #d4af37;
}

.mobile-menu-btn {
    display: none;
    background: none;
    border: none;
    color: #fff;
    font-size: 1.5rem;
    cursor: pointer;
}

.mobile-menu {
    display: none;
    position: fixed;
    top: 80px;
    left: 0;
    width: 100%;
    background: #1a1a1a;
    padding: 1rem 0;
    z-index: 999;
}

.mobile-nav-link {
    display: block;
    color: #fff;
    text-decoration: none;
    padding: 1rem 2rem;
    border-bottom: 1px solid #333;
    transition: background 0.3s ease;
}

.mobile-nav-link:hover {
    background: #333;
    color: #d4af37;
}

/* Buttons */
.btn {
    padding: 12px 24px;
    border: none;
    border-radius: 8px;
    font-weight: 600;
    font-size: 1rem;
    cursor: pointer;
    transition: all 0.3s ease;
    text-decoration: none;
    display: inline-block;
    text-align: center;
}

.btn-primary {
    background: #d4af37;
    color: #1a1a1a;
}

.btn-primary:hover {
    background: #b8941f;
    transform: translateY(-2px);
}

.btn-secondary {
    background: transparent;
    color: #d4af37;
    border: 2px solid #d4af37;
}

.btn-secondary:hover {
    background: #d4af37;
    color: #1a1a1a;
}

/* Hero Section */
.hero {
    background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 100%);
    color: #fff;
    padding: 120px 0 80px;
    min-height: 70vh;
    display: flex;
    align-items: center;
}

.hero-content {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: center;
}

.hero-content h1 {
    font-size: 3rem;
    font-weight: 700;
    margin-bottom: 1.5rem;
    line-height: 1.2;
}

.hero-content p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
    opacity: 0.9;
}

.hero-buttons {
    display: flex;
    gap: 1rem;
}

.hero-image img {
    width: 100%;
    height: 400px;
    object-fit: cover;
    border-radius: 12px;
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
}

/* Sections */
.section {
    padding: 80px 0;
}

.section-title {
    text-align: center;
    font-size: 2.5rem;
    font-weight: 700;
    margin-bottom: 3rem;
    color: #1a1a1a;
}

/* Artists Grid */
.artists-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 2rem;
}

.artist-card {
    background: #fff;
    border-radius: 12px;
    padding: 2rem;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    cursor: pointer;
}

.artist-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 30px rgba(0, 0, 0, 0.15);
}

.artist-header {
    display: flex;
    gap: 1rem;
    align-items: center;
    margin-bottom: 1.5rem;
}

.artist-avatar {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    object-fit: cover;
}

.artist-info h3 {
    font-size: 1.25rem;
    font-weight: 600;
    margin-bottom: 0.5rem;
}

.artist-specialization {
    color: #666;
    font-size: 0.9rem;
}

.artist-stats {
    display: flex;
    justify-content: space-between;
    margin-bottom: 1rem;
}

.stat {
    text-align: center;
}

.stat-value {
    font-weight: 700;
    color: #d4af37;
    font-size: 1.1rem;
}

.stat-label {
    font-size: 0.8rem;
    color: #666;
}

.artist-location {
    color: #666;
    font-size: 0.9rem;
    margin-bottom: 1rem;
}

.artist-bio {
    color: #666;
    font-size: 0.9rem;
    margin-bottom: 1.5rem;
}

.artist-actions {
    display: flex;
    gap: 1rem;
}

.artist-actions .btn {
    flex: 1;
    padding: 8px 16px;
    font-size: 0.9rem;
}

/* Gallery */
.gallery-section {
    background: #f8f9fa;
}

.gallery-filters {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin-bottom: 3rem;
    flex-wrap: wrap;
}

.filter-btn {
    padding: 8px 16px;
    background: #fff;
    border: 2px solid #ddd;
    border-radius: 25px;
    cursor: pointer;
    transition: all 0.3s ease;
    font-weight: 500;
}

.filter-btn.active,
.filter-btn:hover {
    background: #d4af37;
    border-color: #d4af37;
    color: #fff;
}

.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 2rem;
}

.gallery-item {
    background: #fff;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.gallery-item:hover {
    transform: translateY(-5px);
}

.gallery-item img {
    width: 100%;
    height: 250px;
    object-fit: cover;
}

.gallery-item-content {
    padding: 1.5rem;
}

.gallery-item h3 {
    font-size: 1.1rem;
    font-weight: 600;
    margin-bottom: 0.5rem;
}

.gallery-category {
    color: #d4af37;
    font-size: 0.9rem;
    font-weight: 500;
    margin-bottom: 0.5rem;
}

.gallery-price {
    font-size: 1.1rem;
    font-weight: 700;
    color: #1a1a1a;
    margin-bottom: 0.5rem;
}

.gallery-description {
    color: #666;
    font-size: 0.9rem;
}

/* Studios Grid */
.studios-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.studio-card {
    background: #fff;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.studio-card:hover {
    transform: translateY(-5px);
}

.studio-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.studio-content {
    padding: 1.5rem;
}

.studio-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    margin-bottom: 1rem;
}

.studio-name {
    font-size: 1.25rem;
    font-weight: 600;
    margin-bottom: 0.5rem;
}

.studio-rating {
    display: flex;
    align-items: center;
    gap: 0.25rem;
    color: #d4af37;
    font-weight: 600;
}

.studio-address {
    color: #666;
    font-size: 0.9rem;
    margin-bottom: 1rem;
}

.studio-hours {
    color: #666;
    font-size: 0.9rem;
    margin-bottom: 1rem;
}

.studio-services {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-bottom: 1.5rem;
}

.service-tag {
    background: #f0f0f0;
    padding: 4px 8px;
    border-radius: 4px;
    font-size: 0.8rem;
    color: #666;
}

.studio-actions .btn {
    width: 100%;
    margin-bottom: 0.5rem;
}

/* Reviews */
.reviews-section {
    background: #f8f9fa;
}

.reviews-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.review-card {
    background: #fff;
    padding: 2rem;
    border-radius: 12px;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

.review-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 1rem;
}

.review-author {
    font-weight: 600;
    color: #1a1a1a;
}

.review-location {
    color: #666;
    font-size: 0.9rem;
}

.review-rating {
    color: #d4af37;
    font-size: 1.1rem;
}

.review-content {
    color: #666;
    line-height: 1.6;
}

/* Footer */
.footer {
    background: #1a1a1a;
    color: #fff;
    padding: 3rem 0 1rem;
}

.footer-content {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    margin-bottom: 2rem;
}

.footer-section h3,
.footer-section h4 {
    color: #d4af37;
    margin-bottom: 1rem;
}

.footer-section ul {
    list-style: none;
}

.footer-section li {
    margin-bottom: 0.5rem;
}

.footer-section a {
    color: #ccc;
    text-decoration: none;
    transition: color 0.3s ease;
}

.footer-section a:hover {
    color: #d4af37;
}

.footer-bottom {
    text-align: center;
    padding-top: 2rem;
    border-top: 1px solid #333;
    color: #ccc;
}

/* Modal Styles */
.modal {
    display: none;
    position: fixed;
    z-index: 1000;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    animation: fadeIn 0.3s ease;
}

.modal-content {
    background-color: #fff;
    margin: 5% auto;
    padding: 2rem;
    border-radius: 12px;
    width: 90%;
    max-width: 600px;
    max-height: 90vh;
    overflow-y: auto;
    position: relative;
    animation: slideIn 0.3s ease;
}

.modal-large {
    max-width: 800px;
}

.close {
    color: #aaa;
    float: right;
    font-size: 28px;
    font-weight: bold;
    cursor: pointer;
    position: absolute;
    top: 15px;
    right: 20px;
}

.close:hover {
    color: #000;
}

/* Booking Form */
.booking-form {
    margin-top: 2rem;
}

.form-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
    margin-bottom: 1rem;
}

.form-group {
    margin-bottom: 1rem;
}

.form-group label {
    display: block;
    margin-bottom: 0.5rem;
    font-weight: 600;
    color: #333;
}

.form-group input,
.form-group select,
.form-group textarea {
    width: 100%;
    padding: 12px;
    border: 2px solid #ddd;
    border-radius: 8px;
    font-size: 1rem;
    transition: border-color 0.3s ease;
}

.form-group input:focus,
.form-group select:focus,
.form-group textarea:focus {
    outline: none;
    border-color: #d4af37;
}

.form-actions {
    display: flex;
    gap: 1rem;
    justify-content: flex-end;
    margin-top: 2rem;
}

/* Toast Notification */
.toast {
    position: fixed;
    top: 100px;
    right: 20px;
    background: #d4af37;
    color: #1a1a1a;
    padding: 1rem 2rem;
    border-radius: 8px;
    font-weight: 600;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
    transform: translateX(100%);
    transition: transform 0.3s ease;
    z-index: 1001;
}

.toast.show {
    transform: translateX(0);
}

/* Artist Profile Modal Content */
.artist-profile {
    text-align: center;
}

.artist-profile-header {
    margin-bottom: 2rem;
}

.artist-profile-avatar {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 1rem;
}

.artist-profile-name {
    font-size: 1.5rem;
    font-weight: 700;
    margin-bottom: 0.5rem;
}

.artist-profile-specialization {
    color: #d4af37;
    font-size: 1.1rem;
    font-weight: 600;
    margin-bottom: 1rem;
}

.artist-profile-stats {
    display: flex;
    justify-content: center;
    gap: 2rem;
    margin-bottom: 2rem;
}

.artist-portfolio {
    margin: 2rem 0;
}

.portfolio-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1rem;
    margin-top: 1rem;
}

.portfolio-item {
    border-radius: 8px;
    overflow: hidden;
}

.portfolio-item img {
    width: 100%;
    height: 150px;
    object-fit: cover;
}

/* Animations */
@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

@keyframes slideIn {
    from { transform: translateY(-50px); opacity: 0; }
    to { transform: translateY(0); opacity: 1; }
}

/* Responsive Design */
@media (max-width: 768px) {
    .nav-menu {
        display: none;
    }
    
    .mobile-menu-btn {
        display: block;
    }
    
    .hero-content {
        grid-template-columns: 1fr;
        text-align: center;
    }
    
    .hero-content h1 {
        font-size: 2rem;
    }
    
    .hero-buttons {
        justify-content: center;
    }
    
    .section-title {
        font-size: 2rem;
    }
    
    .artists-grid,
    .studios-grid,
    .reviews-grid {
        grid-template-columns: 1fr;
    }
    
    .gallery-grid {
        grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    }
    
    .gallery-filters {
        justify-content: flex-start;
        overflow-x: auto;
        padding-bottom: 1rem;
    }
    
    .form-row {
        grid-template-columns: 1fr;
    }
    
    .form-actions {
        flex-direction: column;
    }
    
    .modal-content {
        width: 95%;
        margin: 10% auto;
        padding: 1.5rem;
    }
}

@media (max-width: 480px) {
    .container {
        padding: 0 15px;
    }
    
    .hero {
        padding: 100px 0 60px;
    }
    
    .section {
        padding: 60px 0;
    }
    
    .hero-buttons {
        flex-direction: column;
        align-items: center;
    }
    
    .btn {
        width: 100%;
    }
    
    .artist-actions {
        flex-direction: column;
    }
    
    .studio-actions .btn {
        margin-bottom: 0.5rem;
    }
}
