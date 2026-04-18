/* RESET AND BOX-SIZING FOR ENTIRE SITE */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6; /* Improved typography spacing */
    color: #3d1b1b;
}

/* NAVIGATION IMPROVEMENTS */
nav {
    background: #2c3e50;
    padding: 1rem 2rem; /* Added padding */
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 2rem; /* Modern spacing between nav items */
}

nav a {
    color: white;
    text-decoration: none;
    padding: 0.5rem 1rem; /* Added padding to nav links */
    border-radius: 5px;
    transition: background 0.3s;
}

nav a:hover {
    background: #34495e;
}

/* SECTION IMPROVEMENTS */
.hero, .about, .services, .contact {
    padding: 4rem 2rem; /* Consistent section padding */
    max-width: 1200px;
    margin: 0 auto;
}

.hero {
    background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), 
                url('hero-image.jpg');
    background-size: cover;
    color: white;
    text-align: center;
    margin-bottom: 0; /* Remove bottom margin for hero */
}

section:not(.hero) {
    margin: 3rem auto; /* Margin between sections */
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    border: 1px solid #eee; /* Subtle border */
}

/* HEADINGS SPACING */
h1, h2, h3 {
    margin-bottom: 1.5rem; /* Space below headings */
    line-height: 1.2;
}

h1 { font-size: 2.5rem; }
h2 { font-size: 2rem; }

/* SERVICES GRID IMPROVEMENTS */
.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem; /* Spacing between service cards */
    margin-top: 2rem;
}

.service-card {
    padding: 2rem; /* Card padding */
    border: 2px solid #ecf0f1;
    border-radius: 10px;
    text-align: center;
    transition: transform 0.3s, box-shadow 0.3s;
}

.service-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 25px rgba(0,0,0,0.15);
}

/* BUTTON IMPROVEMENTS */
.btn {
    display: inline-block;
    padding: 12px 30px; /* Proper button padding */
    background: #3498db;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    border: 2px solid #3498db;
    margin-top: 1rem;
    transition: all 0.3s;
}

.btn:hover {
    background: transparent;
    color: #3498db;
}

/* FORM IMPROVEMENTS */
form {
    max-width: 600px;
    margin: 2rem auto;
}

form input, form textarea {
    width: 100%;
    padding: 12px; /* Input padding */
    margin-bottom: 1rem; /* Space between form fields */
    border: 2px solid #ddd;
    border-radius: 5px;
    font-size: 1rem;
}

form input:focus, form textarea:focus {
    outline: none;
    border-color: #3498db;
    box-shadow: 0 0 5px rgba(52, 152, 219, 0.3);
}

/* FOOTER IMPROVEMENTS */
footer {
    background: #2c3e50;
    color: white;
    text-align: center;
    padding: 2rem;
    margin-top: 3rem;
}

.footer-links {
    display: flex;
    justify-content: center;
    gap: 2rem;
    margin-top: 1rem;
    flex-wrap: wrap;
}

/* RESPONSIVE DESIGN */
@media (max-width: 768px) {
    .hero, .about, .services, .contact {
        padding: 2rem 1rem;
    }
    
    nav ul {
        flex-direction: column;
        gap: 1rem;
        text-align: center;
    }
}# Week-5---Box-Model-Improvements
