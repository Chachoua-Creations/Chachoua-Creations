<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chachoua Creations</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <h1>Chachoua Creations</h1>
            <ul>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h2>Empowering Your Brand with Creativity</h2>
        <p>Let's bring your vision to life together.</p>
        <a href="#portfolio" class="cta-button">Explore My Work</a>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <div class="service-cards">
            <div class="service-card">
                <h3>Graphic Design</h3>
                <p>Creating stunning visuals that represent your brand.</p>
            </div>
            <div class="service-card">
                <h3>Web Development</h3>
                <p>Building responsive, modern websites.</p>
            </div>
            <div class="service-card">
                <h3>Video Production</h3>
                <p>Producing engaging video content for your audience.</p>
            </div>
            <!-- Add more services as needed -->
        </div>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>I'm a young entrepreneur with a passion for creativity and innovation, aspiring to become a top NBA player while building a successful digital studio.</p>
    </section>

    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio-gallery">
            <!-- Add portfolio items here -->
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <form action="#" method="post">
            <input type="text" name="name" placeholder="Your Name">
            <input type="email" name="email" placeholder="Your Email">
            <textarea name="message" placeholder="Your Message"></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Chachoua Creations. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: 'Open Sans', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #000;
    padding: 20px;
    color: #fff;
}

nav h1 {
    font-family: 'Montserrat', sans-serif;
    font-size: 24px;
    margin: 0;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
    margin: 0;
    padding: 0;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background: url('background-image.jpg') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 100px 20px;
}

.hero h2 {
    font-family: 'Montserrat', sans-serif;
    font-size: 48px;
    margin: 0;
}

.cta-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #ffd700;
    color: #000;
    text-decoration: none;
    margin-top: 20px;
    border-radius: 5px;
    font-weight: bold;
}

#services {
    padding: 50px 20px;
    background-color: #fff;
}

.service-cards {
    display: flex;
    justify-content: space-around;
    gap: 20px;
}

.service-card {
    background-color: #f4f4f4;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

#portfolio {
    padding: 50px 20px;
}

.portfolio-gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

#contact {
    background-color: #333;
    color: #fff;
    padding: 50px 20px;
}

#contact form {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

#contact form input, #contact form textarea {
    padding: 10px;
    border-radius: 5px;
    border: none;
}

footer {
    background-color: #000;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}
// Smooth scrolling
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function(e) {
        e.preventDefault();

        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});
/* Ajouter des transitions générales */
* {
    transition: all 0.3s ease-in-out;
}

body {
    font-family: 'Open Sans', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #000;
    padding: 20px;
    color: #fff;
}

nav h1 {
    font-family: 'Montserrat', sans-serif;
    font-size: 24px;
    margin: 0;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
    margin: 0;
    padding: 0;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

/* Animation de l'apparition des sections */
section {
    opacity: 0;
    transform: translateY(20px);
}

section.visible {
    opacity: 1;
    transform: translateY(0);
}

.hero {
    background: url('background-image.jpg') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 100px 20px;
    transition: background-position 0.5s ease;
}

.hero h2 {
    font-family: 'Montserrat', sans-serif;
    font-size: 48px;
    margin: 0;
    animation: slideIn 1s ease-in-out;
}

/* Animation de bouton au survol */
.cta-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #ffd700;
    color: #000;
    text-decoration: none;
    margin-top: 20px;
    border-radius: 5px;
    font-weight: bold;
    transition: background-color 0.3s ease;
}

.cta-button:hover {
    background-color: #ffc107;
}

#services {
    padding: 50px 20px;
    background-color: #fff;
    transition: background-color 0.3s ease;
}

.service-cards {
    display: flex;
    justify-content: space-around;
    gap: 20px;
    transition: transform 0.3s ease;
}

.service-card {
    background-color: #f4f4f4;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.service-card:hover {
    transform: translateY(-10px);
}

/* Animation slide-in pour les services */
@keyframes slideIn {
    0% {
        transform: translateX(-100%);
        opacity: 0;
    }
    100% {
        transform: translateX(0);
        opacity: 1;
    }
}

#portfolio {
    padding: 50px 20px;
}

.portfolio-gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

.portfolio-gallery img {
    width: 100%;
    transition: transform 0.3s ease;
}

.portfolio-gallery img:hover {
    transform: scale(1.05);
}

#contact {
    background-color: #333;
    color: #fff;
    padding: 50px 20px;
}

#contact form {
    display: flex;
    flex-direction: column;
    gap: 15px;
    transition: all 0.3s ease;
}

#contact form input, #contact form textarea {
    padding: 10px;
    border-radius: 5px;
    border: none;
    transition: background-color 0.3s ease;
}

#contact form input:hover, #contact form textarea:hover {
    background-color: #444;
}

footer {
    background-color: #000;
    color: #fff;
    text-align: center;
    padding: 20px 0;
    transition: background-color 0.3s ease;
}
// Fonction pour ajouter la classe 'visible' aux sections lors du défilement
function revealOnScroll() {
    var sections = document.querySelectorAll('section');
    var scrollPosition = window.pageYOffset + window.innerHeight;

    sections.forEach(section => {
        if (section.offsetTop < scrollPosition - 100) {
            section.classList.add('visible');
        }
    });
}

// Appel initial de la fonction pour afficher les sections déjà visibles
revealOnScroll();

// Ecoute de l'événement de défilement pour déclencher l'animation
window.addEventListener('scroll', revealOnScroll);
