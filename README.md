<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Sabir Iazza</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- Menu fixe -->
<nav>
    <ul class="menu">
        <li><a href="#home">Accueil</a></li>
        <li><a href="#about">À propos</a></li>
        <li><a href="#cv">CV</a></li>
        <li><a href="#skills">Compétences</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<!-- Accueil -->
<section id="home">
    <div class="home-content">
        <h1>Salut, je suis Sabir Iazza</h1>
        <p>Étudiant en cybersécurité et informatique</p>
    </div>
</section>

<!-- À propos -->
<section id="about">
    <h2>À propos de moi</h2>
    <p>Salut ! Je suis passionné par la cybersécurité, le développement web et les nouvelles technologies. Je crée des projets web modernes et sécurisés.</p>
</section>

<!-- CV -->
<section id="cv">
    <h2>Mon CV</h2>
    <a href="https://github.com/user-attachments/assets/3d7eecc6-676f-44fe-b5fb-a5aaf84c533d" target="_blank">
        <img src="https://github.com/user-attachments/assets/3d7eecc6-676f-44fe-b5fb-a5aaf84c533d" alt="CV de Sabir Iazza" class="cv-image">
    </a>
    <p><a href="https://github.com/user-attachments/assets/3d7eecc6-676f-44fe-b5fb-a5aaf84c533d" target="_blank" class="btn">Télécharger le CV</a></p>
</section>

<!-- Compétences -->
<section id="skills">
    <h2>Compétences</h2>
    <div class="skills-container">
        <div class="skill" style="--clr:#f44336;">Cybersécurité</div>
        <div class="skill" style="--clr:#2196F3;">Réseaux & Électronique</div>
        <div class="skill" style="--clr:#4CAF50;">Développement Web</div>
        <div class="skill" style="--clr:#FF9800;">Gestion de projets</div>
    </div>
</section>

<!-- Contact -->
<section id="contact">
    <h2>Contact</h2>
    <p>Email : <a href="mailto:sabir.iazza@gmail.com">sabir.iazza@gmail.com</a></p>
    <p>GitHub : <a href="https://github.com/Sabirou">Sabirou</a></p>
</section>

<script src="https://cdn.jsdelivr.net/npm/particles.js"></script>
<script>
// Particles pour fond animé
particlesJS("home", {
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
</script>

</body>
</html>
