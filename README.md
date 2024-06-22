<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bienvenue chez Mo-Djib Consulting</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        /* Styles généraux */
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            overflow-x: hidden; /* Empêche le défilement horizontal */
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
        }

        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
            position: relative;
            z-index: 1;
        }

        /* Styles pour l'en-tête */
        header {
            background: linear-gradient(to right, #3a6186, #89253e);
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }

        /* Styles pour les réseaux sociaux */
        .social {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(100px, 1fr)); /* Utilisation de grid flexible */
            grid-gap: 10px; /* Réduit l'espace entre les éléments */
            justify-content: center;
            align-items: center;
            margin-bottom: 30px;
        }

        .social-link {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background-color: #f5f5f5;
            border-radius: 15px;
            padding: 20px;
            transition: all 0.3s;
            width: 100px;
            height: 100px;
            cursor: pointer;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }

        .social-link i {
            font-size: 3rem;
            color: white; /* Icônes en blanc */
            margin-bottom: 10px;
            transition: color 0.3s;
        }

        .social-link a {
            font-size: 1rem;
            color: white;
            text-decoration: none;
            transition: color 0.3s;
        }

        .social-link:hover {
            transform: translateY(-5px);
        }

        .social-link:hover i {
            color: #3a6186;
        }

        /* Styles pour le slogan */
        .slogan {
            font-size: 1.5rem;
            font-weight: bold;
            margin-bottom: 30px;
        }

        /* Styles pour les coordonnées */
        .contact-info {
            margin-top: 30px;
            text-align: center;
        }

        .contact-info p {
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .contact-info p i {
            margin-right: 5px;
        }

    </style>
</head>

<body>
    <header>
        <img src="https://gist.githubusercontent.com/assets/168087487/3937ec2f-36a3-4158-8638-f5a49547f06c" alt="Logo Mo-Djib Consulting">
        <h1>Bienvenue chez Mo-Djib Consulting</h1>
        <p>Votre partenaire mondial pour la qualité, l'hygiène et la sécurité alimentaire</p>
    </header>
    <div class="container">
        <div class="social">
            <div class="social-link" style="background-color: #3a6186;" onclick="window.location.href='https://www.linkedin.com/company/mo-djib-consulting/'">
                <i class="fab fa-linkedin"></i>
                <a href="https://www.linkedin.com/company/mo-djib-consulting/" target="_blank">LinkedIn</a>
            </div>
            <div class="social-link" style="background-color: #333;" onclick="window.location.href='https://x.com/consulting_Mo?t=p7VLVn2KT1RU1t6nOVjExw&s=09'">
                <i class="fab fa-twitter"></i>
                <a href="https://x.com/consulting_Mo?t=p7VLVn2KT1RU1t6nOVjExw&s=09" target="_blank">Twitter</a>
            </div>
            <div class="social-link" style="background-color: #25d366;" onclick="window.location.href='https://wa.me/message/WZHC7CEMDMMXLXL1'">
                <i
                class="fab fa-whatsapp"></i>
                <a href="https://wa.me/message/WZHC7CEMDMMXLXL1" target="_blank">WhatsApp</a>
            </div>
            <div class="social-link" style="background-color: #1877f2;" onclick="window.location.href='https://www.facebook.com/profile.php?id=100091956626632'">
                <i class="fab fa-facebook"></i>
                <a href="https://www.facebook.com/profile.php?id=100091956626632" target="_blank">Facebook</a>
            </div>
            <div class="social-link" style="background-color: #000;" onclick="window.location.href='https://www.tiktok.com/@modjibconsulting?_t=8nOlFEGRbiX&_r=1'">
                <i class="fab fa-tiktok"></i>
                <a href="https://www.tiktok.com/@modjibconsulting?_t=8nOlFEGRbiX&_r=1" target="_blank">TikTok</a>
            </div>
            <div class="social-link" style="background-color: #c4302b;" onclick="window.location.href='https://youtube.com/@mo-djibconsulting?si=kI44ZYPJQrwN1kfc'">
                <i class="fab fa-youtube"></i>
                <a href="https://youtube.com/@mo-djibconsulting?si=kI44ZYPJQrwN1kfc" target="_blank">YouTube</a>
            </div>
            <div class="social-link" style="background-color: #e1306c;" onclick="window.location.href='https://www.instagram.com/modjib_consulting?igshid=MTJva2FlMHJoamJmZA=='">
                <i class="fab fa-instagram"></i>
                <a href="https://www.instagram.com/modjib_consulting?igshid=MTJva2FlMHJoamJmZA==" target="_blank">Instagram</a>
            </div>
        </div>
        <div class="contact-info">
            <p><i class="fas fa-envelope"></i> Email: modjibconsulting@gmail.com</p>
            <p><i class="fas fa-map-marker-alt"></i> Bureau: rue Moscou, Ibn sina, djibouti, Djibouti</p>
        </div>
    </div>

</body>
</html>
