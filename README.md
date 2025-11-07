/* Général */
body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    color: #fff;
    scroll-behavior: smooth;
    background: linear-gradient(-45deg, #ff6a00, #ee0979, #fcd440, #ff512f);
    background-size: 400% 400%;
    animation: gradientBG 15s ease infinite;
}

/* Gradient animé */
@keyframes gradientBG {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}

/* Menu */
nav {
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    background: rgba(0,0,0,0.5);
    z-index: 1000;
}
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
}
nav ul.menu li a:hover {
    background: rgba(255,255,255,0.2);
}

/* Sections */
section {
    max-width: 900px;
    margin: 100px auto 50px auto;
    padding: 40px 20px;
    background: rgba(0,0,0,0.5);
    border-radius: 15px;
}

/* CV image */
.cv-image {
    max-width: 80%;
    border-radius: 10px;
    cursor: pointer;
}

/* Bouton CV */
.btn {
    display: inline-block;
    padding: 10px 20px;
    margin-top: 15px;
    background: linear-gradient(45deg,#ff6a00,#ee0979,#fcd440,#ff512f);
    border-radius: 10px;
    text-decoration: none;
    color: #fff;
    font-weight: bold;
    transition: transform 0.3s ease;
}
.btn:hover {
    transform: scale(1.1);
}

/* Skills */
.skills-container {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
    justify-content: center;
}
.skill {
    padding: 15px 25px;
    background: rgba(255,255,255,0.1);
    border-radius: 15px;
    font-weight: bold;
    color: var(--clr);
    transition: all 0.3s ease;
}
.skill:hover {
    transform: scale(1.1);
}
