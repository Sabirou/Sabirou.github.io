<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV de Sabir Iazza - Accueil</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <ul class="menu">
            <li><a href="index.html">Accueil</a></li>
            <li><a href="cv.html">CV</a></li>
            <li><a href="skills.html">Compétences</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
    <header>
        <h1>Bienvenue sur mon site</h1>
        <p>Je suis Sabir Iazza, étudiant en cybersécurité et informatique.</p>
    </header>
    <section>
        <h2>À propos de moi</h2>
        <p>Salut ! Je suis passionné par la cybersécurité, le développement web et les nouvelles technologies. Je crée des projets web modernes et sécurisés.</p>
    </section>
</body>
</html>
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
    <nav>
        <ul class="menu">
            <li><a href="index.html">Accueil</a></li>
            <li><a href="cv.html">CV</a></li>
            <li><a href="skills.html">Compétences</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
    <header>
        <h1>Mon CV</h1>
        <p>Clique sur l'image pour voir le CV en grand</p>
    </header>
    <section>
        <a href="https://github.com/user-attachments/assets/3d7eecc6-676f-44fe-b5fb-a5aaf84c533d" target="_blank">
            <img src="https://github.com/user-attachments/assets/3d7eecc6-676f-44fe-b5fb-a5aaf84c533d" alt="CV de Sabir Iazza" style="max-width:80%;border-radius:10px;">
        </a>
        <p><a href="https://github.com/user-attachments/assets/3d7eecc6-676f-44fe-b5fb-a5aaf84c533d" target="_blank">Télécharger le CV</a></p>
    </section>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Compétences - Sabir Iazza</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <ul class="menu">
            <li><a href="index.html">Accueil</a></li>
            <li><a href="cv.html">CV</a></li>
            <li><a href="skills.html">Compétences</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
    <header>
        <h1>Mes compétences</h1>
    </header>
    <section>
        <div class="skills-container">
            <div class="skill" style="--clr:#f44336;">Cybersécurité</div>
            <div class="skill" style="--clr:#2196F3;">Réseaux & Électronique</div>
            <div class="skill" style="--clr:#4CAF50;">Développement Web</div>
            <div class="skill" style="--clr:#FF9800;">Gestion de projets</div>
        </div>
    </section>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact - Sabir Iazza</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <ul class="menu">
            <li><a href="index.html">Accueil</a></li>
            <li><a href="cv.html">CV</a></li>
            <li><a href="skills.html">Compétences</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
    <header>
        <h1>Contactez-moi</h1>
    </header>
    <section>
        <p>Email : <a href="mailto:sabir.iazza@gmail.com">sabir.iazza@gmail.com</a></p>
        <p>GitHub : <a href="https://github.com/Sabirou">Sabirou</a></p>
    </section>
</body>
</html>
/* Général */
body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    scroll-behavior: smooth;
    color: #fff;
    background: linear-gradient(-45deg, #ff6a00, #ee0979, #fcd440, #ff512f);
    background-size: 400% 400%;
    animation: gradientBG 15s ease infinite;
}
/* Animation du gradient */
@keyframes gradientBG {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}
/* Menu */
nav ul.menu {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 30px;
    margin: 0;
    padding: 15px 0;
}
nav ul.menu li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.1em;
    padding: 8px 15px;
    border-radius: 10px;
    transition: all 0.3s ease;
    position: relative;
}
nav ul.menu li a:hover {
    color: #fff;
    background: linear-gradient(45deg, #ff6a00, #ee0979, #fcd440, #ff512f);
    box-shadow: 0 0 10px #ff6a00, 0 0 20px #ee0979, 0 0 30px #fcd440, 0 0 40px #ff512f;
    transform: scale(1.1);
}
nav ul.menu li a::after {
    content: '';
    position: absolute;
    left: 50%;
    bottom: -5px;
    width: 0%;
    height: 3px;
    background: #FFD700;
    transition: 0.4s;
    transform: translateX(-50%);
    border-radius: 2px;
}
nav ul.menu li a:hover::after {
    width: 80%;
}
/* Sections */
section {
    max-width: 900px;
    margin: 40px auto;
    padding: 40px 20px;
    background: rgba(0,0,0,0.6);
    border-radius: 15px;
}
