// Sample Data - Matches the React app data
const sampleData = {
    artists: [
        {
            id: 1,
            name: "Raj Mehta",
            specialization: "Traditional & Geometric Hand Tattoos",
            location: "Bandra, Mumbai",
            rating: "4.9",
            reviewCount: 127,
            minPrice: 3000,
            maxPrice: 15000,
            imageUrl: "https://pixabay.com/get/ga26445fc3bcecc8545c48367bb15bc74d9ad0e700d366d42241614dba113c77bd21c192b7f50d716ecb7112f0cf43a284b90c6da3b2d2803cbcca678b9701650_1280.jpg",
            bio: "Expert in traditional Indian and geometric patterns with 8+ years of experience.",
            experience: 8,
            phone: "+91 98765 43210",
            email: "raj@inkculture.in",
            instagramUrl: "@raj_tattoo_artist",
            portfolioImages: [
                "https://images.unsplash.com/photo-1598300042247-d088f8ab3a91?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&h=400",
                "https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&h=400"
            ]
        },
        {
            id: 2,
            name: "Priya Sharma",
            specialization: "Fine Line & Minimalist Hand Designs",
            location: "CP, New Delhi",
            rating: "4.8",
            reviewCount: 89,
            minPrice: 2500,
            maxPrice: 12000,
            imageUrl: "https://pixabay.com/get/ge05f8a6cf665ec48dff40109fe619599456395aa017819dcba9a56143b2d154d00d7f7b304505fbe29138e3d5f4a17d4bf05b03bd7d64adbf3ebd4ec3cce1c64_1280.jpg",
            bio: "Specialized in delicate fine line work and minimalist designs.",
            experience: 6,
            phone: "+91 87654 32109",
            email: "priya@sacredarts.in",
            instagramUrl: "@priya_fineline",
            portfolioImages: [
                "https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&h=400",
                "https://images.unsplash.com/photo-1581833971358-2c8b550f87b3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&h=400"
            ]
        },
        {
            id: 3,
            name: "Arjun Singh",
            specialization: "Mandala & Spiritual Hand Art",
            location: "Koramangala, Bangalore",
            rating: "4.9",
            reviewCount: 156,
            minPrice: 4000,
            maxPrice: 18000,
            imageUrl: "https://images.unsplash.com/photo-1598300042247-d088f8ab3a91?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&h=300",
            bio: "Master of mandala and spiritual tattoo art with deep cultural understanding.",
            experience: 10,
            phone: "+91 76543 21098",
            email: "arjun@electricneedle.in",
            instagramUrl: "@arjun_mandala_art",
            portfolioImages: [
                "https://images.unsplash.com/photo-1595476108010-b4d1f102b1b1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&h=400",
                "https://images.unsplash.com/photo-1565058379802-bbe93b2f703a?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&h=400"
            ]
        }
    ],
    
    studios: [
        {
            id: 1,
            name: "Ink Culture Studio",
            address: "123 Linking Road, Bandra West, Mumbai - 400050",
            phone: "+91 98765 43210",
            hours: "Mon-Sun: 11:00 AM - 9:00 PM",
            rating: "4.8",
            reviewCount: 94,
            imageUrl: "https://pixabay.com/get/gd0b055ab0a3084e9afdb415b29b0f25b3523886f96e92897f45a3ef8c56a9cd505d87872a8c0a8dc39413a328a8cf68b99661627b90681ba1c9e0c3b97df4a61_1280.jpg",
            services: ["Hand Tattoos", "Cover-ups", "Custom Design"],
            website: "www.inkculture.in",
            email: "info@inkculture.in"
        },
        {
            id: 2,
            name: "Sacred Arts Tattoo",
            address: "45 Hauz Khas Village, New Delhi - 110016",
            phone: "+91 87654 32109",
            hours: "Tue-Sun: 12:00 PM - 10:00 PM",
            rating: "4.9",
            reviewCount: 67,
            imageUrl: "https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&h=300",
            services: ["Spiritual Art", "Geometric", "Fine Line"],
            website: "www.sacredarts.in",
            email: "hello@sacredarts.in"
        },
        {
            id: 3,
            name: "Electric Needle Co.",
            address: "78 Brigade Road, Bangalore - 560001",
            phone: "+91 76543 21098",
            hours: "Mon-Sat: 10:00 AM - 8:00 PM",
            rating: "4.7",
            reviewCount: 112,
            imageUrl: "https://pixabay.com/get/gd8695d6cb3ddfc2e9c0b93760d954b88171b58eff706cc91683bba7f2d6d81baa7b16699fabc787434a5fbbc64796628abe85e985def8581aa223e7367b641d7_1280.jpg",
            services: ["Traditional", "Realism", "Colorwork"],
            website: "www.electricneedle.in",
            email: "contact@electricneedle.in"
        },
        {
            id: 4,
            name: "Minimal Ink Studio",
            address: "22 Park Street, Kolkata - 700016",
            phone: "+91 65432 10987",
            hours: "Wed-Mon: 1:00 PM - 9:00 PM",
            rating: "4.8",
            reviewCount: 78,
            imageUrl: "https://images.unsplash.com/photo-1581833971358-2c8b550f87b3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&h=300",
            services: ["Minimalist", "Line Work", "Lettering"],
            website: "www.minimalink.in",
            email: "studio@minimalink.in"
        }
    ],
    
    designs: [
        {
            id: 1,
            title: "Intricate Mandala Hand Design",
            category: "Mandala",
            imageUrl: "https://images.unsplash.com/photo-1598300042247-d088f8ab3a91?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&h=400",
            artistId: 1,
            price: 8000,
            description: "Beautiful mandala pattern covering the back of hand"
        },
        {
            id: 2,
            title: "Fine Line Floral Pattern",
            category: "Minimalist",
            imageUrl: "https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&h=400",
            artistId: 2,
            price: 5500,
            description: "Elegant fine line flowers extending across fingers"
        },
        {
            id: 3,
            title: "Geometric Sacred Symbols",
            category: "Geometric",
            imageUrl: "https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&h=400",
            artistId: 3,
            price: 12000,
            description: "Complex geometric patterns with spiritual elements"
        },
        {
            id: 4,
            title: "Traditional Rose Design",
            category: "Traditional",
            imageUrl: "https://images.unsplash.com/photo-1581833971358-2c8b550f87b3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&h=400",
            artistId: 1,
            price: 7500,
            description: "Classic rose with detailed shading and highlights"
        },
        {
            id: 5,
            title: "Minimalist Arrow Pattern",
            category: "Minimalist",
            imageUrl: "https://images.unsplash.com/photo-1565058379802-bbe93b2f703a?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&h=400",
            artistId: 2,
            price: 3500,
            description: "Simple arrow and line work across fingers"
        },
        {
            id: 6,
            title: "Ornate Henna-Style Design",
            category: "Traditional",
            imageUrl: "https://images.unsplash.com/photo-1595476108010-b4d1f102b1b1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&h=400",
            artistId: 3,
            price: 10000,
            description: "Detailed henna-inspired patterns covering palm"
        },
        {
            id: 7,
            title: "Abstract Watercolor Style",
            category: "Modern",
            imageUrl: "https://images.unsplash.com/photo-1578662996442-48f60103fc96?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&h=400",
            artistId: 1,
            price: 9500,
            description: "Watercolor-inspired abstract design"
        },
        {
            id: 8,
            title: "Celtic Knot Pattern",
            category: "Traditional",
            imageUrl: "https://images.unsplash.com/photo-1540553016722-983e48a2cd10?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=400&h=400",
            artistId: 2,
            price: 6500,
            description: "Celtic knots wrapping around hand and wrist"
        }
    ],
    
    reviews: [
        {
            id: 1,
            authorName: "Ananya Patel",
            location: "Mumbai",
            rating: 5,
            content: "Raj created an absolutely stunning mandala design on my hand. The detail and precision were incredible. The studio was clean and professional. Highly recommend!",
            artistId: 1
        },
        {
            id: 2,
            authorName: "Vikram Reddy",
            location: "Delhi",
            rating: 5,
            content: "Priya's fine line work is exceptional. She understood exactly what I wanted and delivered beyond my expectations. The healing process was smooth too.",
            artistId: 2
        },
        {
            id: 3,
            authorName: "Sneha Gupta",
            location: "Bangalore",
            rating: 5,
            content: "Amazing experience at Electric Needle Co. The geometric design on my hand came out perfect. Professional service from consultation to aftercare.",
            artistId: 3
        }
    ]
};

// Global variables
let currentFilter = 'All Designs';

// DOM Content Loaded
document.addEventListener('DOMContentLoaded', function() {
    initializeApp();
});

// Initialize App
function initializeApp() {
    renderArtists();
    renderStudios();
    renderDesigns();
    renderReviews();
    setupEventListeners();
}

// Setup Event Listeners
function setupEventListeners() {
    // Mobile menu toggle
    const mobileMenuBtn = document.getElementById('mobileMenuBtn');
    const mobileMenu = document.getElementById('mobileMenu');
    
    mobileMenuBtn.addEventListener('click', function() {
        mobileMenu.style.display = mobileMenu.style.display === 'block' ? 'none' : 'block';
    });

    // Close mobile menu when clicking on links
    document.querySelectorAll('.mobile-nav-link').forEach(link => {
        link.addEventListener('click', function() {
            mobileMenu.style.display = 'none';
        });
    });

    // Gallery filters
    document.querySelectorAll('.filter-btn').forEach(btn => {
        btn.addEventListener('click', function() {
            const category = this.getAttribute('data-category');
            filterDesigns(category);
            
            // Update active filter button
            document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
            this.classList.add('active');
        });
    });

    // Booking form
    const bookingForm = document.getElementById('bookingForm');
    bookingForm.addEventListener('submit', handleBookingSubmit);

    // Smooth scrolling for navigation
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
        anchor.addEventListener('click', function (e) {
            e.preventDefault();
            const target = document.querySelector(this.getAttribute('href'));
            if (target) {
                target.scrollIntoView({
                    behavior: 'smooth',
                    block: 'start'
                });
            }
        });
    });
}

// Render Artists
function renderArtists() {
    const artistsGrid = document.getElementById('artistsGrid');
    artistsGrid.innerHTML = '';

    sampleData.artists.forEach(artist => {
        const artistCard = createArtistCard(artist);
        artistsGrid.appendChild(artistCard);
    });
}

// Create Artist Card
function createArtistCard(artist) {
    const card = document.createElement('div');
    card.className = 'artist-card';
    card.onclick = () => showArtistProfile(artist);

    card.innerHTML = `
        <div class="artist-header">
            <img src="${artist.imageUrl}" alt="${artist.name}" class="artist-avatar" />
            <div class="artist-info">
                <h3>${artist.name}</h3>
                <p class="artist-specialization">${artist.specialization}</p>
            </div>
        </div>
        <div class="artist-stats">
            <div class="stat">
                <div class="stat-value">${artist.rating} ⭐</div>
                <div class="stat-label">Rating</div>
            </div>
            <div class="stat">
                <div class="stat-value">${artist.reviewCount}</div>
                <div class="stat-label">Reviews</div>
            </div>
            <div class="stat">
                <div class="stat-value">${artist.experience}y</div>
                <div class="stat-label">Experience</div>
            </div>
        </div>
        <p class="artist-location"><i class="fas fa-map-marker-alt"></i> ${artist.location}</p>
        <p class="artist-bio">${artist.bio}</p>
        <div class="artist-actions">
            <button class="btn btn-primary" onclick="event.stopPropagation(); showArtistProfile(${JSON.stringify(artist).replace(/"/g, '&quot;')})">View Portfolio</button>
            <button class="btn btn-secondary" onclick="event.stopPropagation(); openBookingModal()">Book Now</button>
        </div>
    `;

    return card;
}

// Show Artist Profile
function showArtistProfile(artist) {
    const modal = document.getElementById('artistModal');
    const modalContent = document.getElementById('artistModalContent');
    
    modalContent.innerHTML = `
        <div class="artist-profile">
            <div class="artist-profile-header">
                <img src="${artist.imageUrl}" alt="${artist.name}" class="artist-profile-avatar" />
                <h2 class="artist-profile-name">${artist.name}</h2>
                <p class="artist-profile-specialization">${artist.specialization}</p>
                <div class="artist-profile-stats">
                    <div class="stat">
                        <div class="stat-value">${artist.rating} ⭐</div>
                        <div class="stat-label">Rating</div>
                    </div>
                    <div class="stat">
                        <div class="stat-value">${artist.reviewCount}</div>
                        <div class="stat-label">Reviews</div>
                    </div>
                    <div class="stat">
                        <div class="stat-value">${artist.experience} years</div>
                        <div class="stat-label">Experience</div>
                    </div>
                </div>
            </div>
            
            <div class="artist-details">
                <p><strong>Location:</strong> ${artist.location}</p>
                <p><strong>Price Range:</strong> ₹${artist.minPrice.toLocaleString()} - ₹${artist.maxPrice.toLocaleString()}</p>
                <p><strong>Phone:</strong> ${artist.phone}</p>
                <p><strong>Email:</strong> ${artist.email}</p>
                <p><strong>Instagram:</strong> ${artist.instagramUrl}</p>
                <p><strong>Bio:</strong> ${artist.bio}</p>
            </div>
            
            <div class="artist-portfolio">
                <h3>Portfolio</h3>
                <div class="portfolio-grid">
                    ${artist.portfolioImages.map(img => `
                        <div class="portfolio-item">
                            <img src="${img}" alt="Portfolio work" />
                        </div>
                    `).join('')}
                </div>
            </div>
            
            <div style="margin-top: 2rem; text-align: center;">
                <button class="btn btn-primary" onclick="openBookingModal()" style="margin-right: 1rem;">Book Consultation</button>
                <button class="btn btn-secondary" onclick="closeArtistModal()">Close</button>
            </div>
        </div>
    `;
    
    modal.style.display = 'block';
}

// Close Artist Modal
function closeArtistModal() {
    document.getElementById('artistModal').style.display = 'none';
}

// Render Studios
function renderStudios() {
    const studiosGrid = document.getElementById('studiosGrid');
    studiosGrid.innerHTML = '';

    sampleData.studios.forEach(studio => {
        const studioCard = createStudioCard(studio);
        studiosGrid.appendChild(studioCard);
    });
}

// Create Studio Card
function createStudioCard(studio) {
    const card = document.createElement('div');
    card.className = 'studio-card';

    card.innerHTML = `
        <img src="${studio.imageUrl}" alt="${studio.name}" />
        <div class="studio-content">
            <div class="studio-header">
                <div>
                    <h3 class="studio-name">${studio.name}</h3>
                    <p class="studio-address">${studio.address}</p>
                </div>
                <div class="studio-rating">
                    <span>${studio.rating} ⭐</span>
                    <div style="font-size: 0.8rem; color: #666;">(${studio.reviewCount} reviews)</div>
                </div>
            </div>
            
            <p class="studio-hours"><i class="fas fa-clock"></i> ${studio.hours}</p>
            
            <div class="studio-services">
                ${studio.services.map(service => <span class="service-tag">${service}</span>).join('')}
            </div>
            
            <div class="studio-actions">
                <button class="btn btn-primary" onclick="openBookingModal()">Book Appointment</button>
                <div style="display: flex; gap: 0.5rem; margin-top: 0.5rem;">
                    <a href="tel:${studio.phone}" class="btn btn-secondary" style="flex: 1;">Call</a>
                    <a href="mailto:${studio.email}" class="btn btn-secondary" style="flex: 1;">Email</a>
                </div>
            </div>
        </div>
    `;

    return card;
}

// Render Designs
function renderDesigns(category = 'All Designs') {
    const galleryGrid = document.getElementById('galleryGrid');
    galleryGrid.innerHTML = '';

    const filteredDesigns = category === 'All Designs' 
        ? sampleData.designs 
        : sampleData.designs.filter(design => design.category === category);

    filteredDesigns.forEach(design => {
        const designCard = createDesignCard(design);
        galleryGrid.appendChild(designCard);
    });
}

// Create Design Card
function createDesignCard(design) {
    const card = document.createElement('div');
    card.className = 'gallery-item';

    const artist = sampleData.artists.find(a => a.id === design.artistId);

    card.innerHTML = `
        <img src="${design.imageUrl}" alt="${design.title}" />
        <div class="gallery-item-content">
            <h3>${design.title}</h3>
            <p class="gallery-category">${design.category}</p>
            <p class="gallery-price">₹${design.price.toLocaleString()}</p>
            <p class="gallery-description">${design.description}</p>
            ${artist ? <p style="font-size: 0.8rem; color: #666; margin-top: 0.5rem;">by ${artist.name}</p> : ''}
        </div>
    `;

    return card;
}

// Filter Designs
function filterDesigns(category) {
    currentFilter = category;
    renderDesigns(category);
}

// Render Reviews
function renderReviews() {
    const reviewsGrid = document.getElementById('reviewsGrid');
    reviewsGrid.innerHTML = '';

    sampleData.reviews.forEach(review => {
        const reviewCard = createReviewCard(review);
        reviewsGrid.appendChild(reviewCard);
    });
}

// Create Review Card
function createReviewCard(review) {
    const card = document.createElement('div');
    card.className = 'review-card';

    const stars = '⭐'.repeat(review.rating);

    card.innerHTML = `
        <div class="review-header">
            <div>
                <div class="review-author">${review.authorName}</div>
                <div class="review-location">${review.location}</div>
            </div>
            <div class="review-rating">${stars}</div>
        </div>
        <p class="review-content">${review.content}</p>
    `;

    return card;
}

// Booking Modal Functions
function openBookingModal() {
    document.getElementById('bookingModal').style.display = 'block';
}

function closeBookingModal() {
    document.getElementById('bookingModal').style.display = 'none';
}

// Handle Booking Form Submit
function handleBookingSubmit(e) {
    e.preventDefault();
    
    // Get form data
    const formData = new FormData(e.target);
    const bookingData = Object.fromEntries(formData);
    
    // Simple validation
    if (!bookingData.name || !bookingData.phone || !bookingData.email || !bookingData.city) {
        showToast('Please fill in all required fields');
        return;
    }

    // Simulate booking submission
    setTimeout(() => {
        showToast('Consultation booked successfully! We\'ll contact you within 24 hours.');
        closeBookingModal();
        e.target.reset();
    }, 1000);
}

// Show Toast Notification
function showToast(message) {
    const toast = document.getElementById('toast');
    const toastMessage = document.getElementById('toastMessage');
    
    toastMessage.textContent = message;
    toast.classList.add('show');
    
    setTimeout(() => {
        toast.classList.remove('show');
    }, 3000);
}

// Utility Functions
function scrollToSection(sectionId) {
    const section = document.getElementById(sectionId);
    if (section) {
        section.scrollIntoView({
            behavior: 'smooth',
            block: 'start'
        });
    }
}

// Close modals when clicking outside
window.onclick = function(event) {
    const bookingModal = document.getElementById('bookingModal');
    const artistModal = document.getElementById('artistModal');
    
    if (event.target === bookingModal) {
        closeBookingModal();
    }
    
    if (event.target === artistModal) {
        closeArtistModal();
    }
}
