Patryk Borkowski Clone Linktree

Ce projet est une simple page HTML/CSS qui sert de clone d'une page de destination personnelle de type Linktree pour Patryk Borkowski. La page fournit un accès rapide aux travaux récents de Patryk Borkowski, à sa page "À propos de moi" et à ses informations de contact, ainsi que des liens vers ses profils de médias sociaux.

Structure du Projet
Le projet se compose des fichiers et répertoires principaux suivants :

index.html : Le fichier HTML principal contenant la structure de la page web.
style.css : Le fichier CSS utilisé pour styliser la page web.
assets/ : Un répertoire contenant les ressources d'images utilisées sur la page web.
Fichier HTML : index.html
Le fichier index.html contient la structure HTML de la page web. Voici une répartition des sections clés :

Section Head : 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Patryk Borkowski Clone Linktree</title>
    <link rel="stylesheet" href="style.css">
</head>
Définit l'encodage des caractères en UTF-8.
Ajuste la mise en page pour qu'elle soit réactive sur tous les appareils avec la balise meta viewport.
Définit le titre de la page comme "Patryk Borkowski Clone Linktree".
Lie le fichier CSS pour styliser la page web.

Section Body : 
<body class="body">
    <div class="global">
        <section class="section1">
            <img class="photo" src="assets/Rectangle 6.png" alt="japanese woman on a light background">
            <h1 class="h1">
                PATRYK BORKOWSKI
            </h1>
            <h2 class="h2">
                I orchestrate immersive experiences that dance on<br> the precipice of imagination and logic
            </h2>
            <div class="div-section-2">
                <a class="button-link" href="https://patryk-borkowski.webflow.io/" target="_blank">
                    <button class="recent-work">RECENT WORK</button>
                </a>
                <a class="button-link" href="https://patryk-borkowski.webflow.io/" target="_blank">
                    <button class="about-me">ABOUT ME</button>
                </a>
                <a class="button-link" href="https://patryk-borkowski.webflow.io/" target="_blank">
                    <button class="contact">CONTACT</button>
                </a>
            </div>
        </section>
        <section class="section3">
            <div class="social-media">
                <a href="https://patryk-borkowski.webflow.io/" target="_blank">
                    <img src="assets/Vector.svg" alt="instagram icon">
                </a>
                <a href="https://patryk-borkowski.webflow.io/" target="_blank">
                    <img src="assets/Vector (1).svg" alt="twitter icon">
                </a>
                <a href="https://patryk-borkowski.webflow.io/" target="_blank">
                    <img src="assets/Vector (2).svg" alt="facebook icon">
                </a>
            </div>
        </section>
    </div>
</body>
Contient la structure principale de la page web avec les sections pour l'image, les boutons de navigation et les icônes des médias sociaux.
section1 contient la photo de profil, le nom et la description de Patryk Borkowski.
div-section-2 contient les boutons menant aux travaux récents, à propos de moi, et contact.
section3 contient les liens vers les profils de médias sociaux.
Fichier CSS : style.css
Le fichier style.css contient les styles nécessaires pour rendre la page web attrayante et fonctionnelle.

Styles pour les Sections et Éléments : 
.section1 {
    width: 360px;
    height: 800px;
}

.photo {
    margin-top: 148px;
}

.h1 {
    font-family: DM Serif Display;
    font-weight: 500;
    font-size: 36px;
    text-align: center;
    margin-top: 16px;
    margin-bottom: 0px;
    color: rgba(21, 21, 21, 1);
}

.h2 {
    font-family: Public Sans;
    font-size: 12px;
    text-align: center;
    margin-top: 4px;
    font-weight: 500;
    color: rgba(21, 21, 21, 1);
}

.div-section-2 {
    margin-top: 86px;
}

.recent-work, .about-me, .contact {
    display: block;
    background-color: rgba(224, 0, 94, 1);
    border: none;
    font-family: Public Sans;
    font-weight: 600;
    color: rgba(249, 249, 249, 1);
    font-size: 14px;
    padding-top: 18px;
    padding-bottom: 18px;
    width: 100%;
    cursor: pointer;
}

.recent-work:hover, .about-me:hover, .contact:hover {
    background-color: rgba(21, 21, 21, 1);
    transition: 0.2s ease-in-out;
}

.about-me {
    margin-top: 16px;
}

.contact {
    margin-top: 16px;
    margin-left: auto;
    position: relative;
    overflow: hidden;
}

.social-media {
    display: flex;
    justify-content: space-between;
    margin-left: 80px;
    margin-right: 80px;
    margin-top: -80px;
}

.button-link {
    text-decoration: none;
}

.body {
    display: flex;
    justify-content: center;
}
Définit les styles pour les sections et éléments de la page, y compris les images, les titres, les boutons, et les icônes des médias sociaux.
Utilise des propriétés CSS telles que margin, padding, font-family, font-size, color, et background-color pour styliser les éléments.
Ajoute des effets de survol (hover) pour les boutons avec une transition douce.
Répertoire des Assets : assets/
Le répertoire assets/ contient toutes les images utilisées sur la page web, telles que :

Rectangle 6.png : Image de la femme japonaise.
Vector.svg : Icône Instagram.
Vector (1).svg : Icône Twitter.
Vector (2).svg : Icône Facebook.
Instructions pour Exécuter le Projet : 
Clonez le dépôt ou téléchargez les fichiers du projet.
Assurez-vous que les fichiers index.html, style.css, et le répertoire assets/ sont dans le même répertoire.
Ouvrez index.html dans un navigateur web pour voir la page en action.
