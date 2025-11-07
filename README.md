<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV de Sabir Iazza</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Particles.js -->
    <div id="particles-js"></div>

    <!-- Menu de navigation -->
    <nav>
        <ul class="menu">
            <li><a href="#about">À propos</a></li>
            <li><a href="#cv">CV</a></li>
            <li><a href="#skills">Compétences</a></li>
            <li><a href="#experience">Expériences</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Header avec image et titre -->
    <header>
        <div class="header-content">
            <a href="https://github.com/user-attachments/assets/3d7eecc6-676f-44fe-b5fb-a5aaf84c533d" target="_blank">
                <img src="https://github.com/user-attachments/assets/3d7eecc6-676f-44fe-b5fb-a5aaf84c533d" alt="CV de Sabir Iazza" class="cv-image">
            </a>
            <h1 class="animate-title">Sabir Iazza</h1>
            <p class="animate-subtitle">Étudiant en cybersécurité et informatique</p>
        </div>
    </header>

    <!-- À propos -->
    <section id="about" class="animate-section">
        <h2>À propos de moi</h2>
        <p>Salut ! Je suis Sabir, passionné par la cybersécurité, le développement web et les nouvelles technologies. Je crée des projets web modernes et sécurisés.</p>
    </section>

    <!-- CV -->
    <section id="cv" class="animate-section">
        <h2>Mon CV</h2>
        <div class="cv-container">
            <a href="https://github.com/user-attachments/assets/3d7eecc6-676f-44fe-b5fb-a5aaf84c533d" target="_blank">
                <img src="https://github.com/user-attachments/assets/3d7eecc6-676f-44fe-b5fb-a5aaf84c533d" alt="CV de Sabir Iazza">
            </a>
            <p><a href="https://github.com/user-attachments/assets/3d7eecc6-676f-44fe-b5fb-a5aaf84c533d" target="_blank">Télécharger le CV</a></p>
        </div>
    </section>

    <!-- Compétences -->
    <section id="skills" class="animate-section">
        <h2>Compétences</h2>
        <div class="skills-container">
            <div class="skill" style="--clr:#f44336;">Cybersécurité</div>
            <div class="skill" style="--clr:#2196F3;">Réseaux & Électronique</div>
            <div class="skill" style="--clr:#4CAF50;">Développement Web</div>
            <div class="skill" style="--clr:#FF9800;">Gestion de projets</div>
        </div>
    </section>

    <!-- Expériences -->
    <section id="experience" class="animate-section">
        <h2>Expériences</h2>
        <ul>
            <li>Stage en réparation de téléphones – 2025</li>
            <li>Stage dans le bâtiment – 2024</li>
            <li>Certification : Introduction à la cybersécurité</li>
        </ul>
    </section>

    <!-- Contact -->
    <section id="contact" class="animate-section">
        <h2>Contact</h2>
        <p>Email : <a href="mailto:sabir.iazza@gmail.com">sabir.iazza@gmail.com</a></p>
        <p>GitHub : <a href="https://github.com/Sabirou">Sabirou</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Sabir Iazza</p>
    </footer>

    <!-- Scripts -->
    <script src="https://cdn.jsdelivr.net/npm/particles.js"></script>
    <script>
        // Particles.js
        particlesJS("particles-js", {
            "particles": {
                "number": { "value": 60 },
                "color": { "value": ["#ff4081","#2196F3","#4CAF50","#FF9800"] },
                "shape": { "type": "circle" },
                "opacity": { "value": 0.7 },
                "size": { "value": 4 },
                "line_linked": { "enable": true, "distance": 150, "color": "#ffffff", "opacity": 0.4, "width": 1 },
                "move": { "enable": true, "speed": 3, "direction": "none", "random": true, "straight": false }
            },
            "interactivity": {
                "events": { "onhover": { "enable": true, "mode": "repulse" } }
            },
            "retina_detect": true
        });

        // Animation au scroll
        const sections = document.querySelectorAll('.animate-section');
        const observer = new IntersectionObserver((entries, observer) => {
            entries.forEach(entry => {
                if(entry.isIntersecting){
                    entry.target.classList.add('show');
                    observer.unobserve(entry.target);
                }
            });
        }, { threshold: 0.2 });

        sections.forEach(section => observer.observe(section));
    </script>

</body>
</html>
