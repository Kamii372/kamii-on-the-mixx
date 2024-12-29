# kamii-on-the-mixx
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kamii on the Mix - Studio d'Enregistrement</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>KAMII ON THE MIX</h1>
            <p>Le studio d'enregistrement de vos rêves !</p>
        </div>
    </header>

    <section class="intro">
        <h2>Bienvenue dans l'univers de Kamii on the Mix</h2>
        <p>Nous offrons des services d'enregistrement de haute qualité, un espace créatif pour tous vos projets musicaux.</p>
        <img src="photo-studio.jpg" alt="Studio d'enregistrement" class="studio-image">
    </section>

    <section class="services">
        <h2>Nos Services</h2>
        <ul>
            <li>Enregistrement vocal</li>
            <li>Mixage audio</li>
            <li>Production musicale</li>
            <li>Mastering audio</li>
        </ul>
    </section>

    <section class="contact">
        <h2>Contactez-nous</h2>
        <p>Pour plus d'informations ou pour prendre rendez-vous, contactez-nous directement via WhatsApp ou sur notre page Facebook !</p>
        <a href="https://wa.me/0343117350" target="_blank" class="whatsapp-link">Envoyer un message sur WhatsApp</a>
        <a href="https://www.facebook.com/KAMII-ON-THE-MIX" target="_blank" class="facebook-link">Visitez notre page Facebook</a>
    </section>

    <footer>
        <p>&copy; 2024 Kamii on the Mix | Tous droits réservés</p>
    </footer>

</body>
</html>

/* Mise en page et style général */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

header h1 {
    font-size: 3em;
    margin: 0;
}

header p {
    font-size: 1.2em;
}

.intro, .services, .contact {
    padding: 20px;
    text-align: center;
}

.studio-image {
    max-width: 100%;
    height: auto;
    margin-top: 20px;
}

.services ul {
    list-style: none;
    padding: 0;
}

.services li {
    font-size: 1.2em;
    margin: 10px 0;
}

.contact a {
    display: inline-block;
    padding: 10px 20px;
    margin: 10px;
    background-color: #25D366; /* WhatsApp */
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-size: 1.2em;
}

.contact a.facebook-link {
    background-color: #1877F2; /* Facebook */
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: absolute;
    width: 100%;
    bottom: 0;
}
