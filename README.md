<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Am Waldrand</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e0e8d3;
            text-align: center;
        }
        header {
            background-color: #a4b494;
            padding: 20px;
            font-size: 2em;
            font-family: 'Brush Script MT', cursive;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .image-placeholder {
            width: 300px;
            height: 200px;
            background-color: #c3d6a2;
            margin: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5em;
        }
        .footer {
            background-color: #a4b494;
            padding: 20px;
            margin-top: 20px;
        }
        iframe {
            width: 100%;
            height: 300px;
            border: 0;
        }
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <header>
        Am Waldrand
        <a href="https://www.instagram.com/jasmin.froelke/" target="_blank">
            <img src="instagram_icon.png" alt="Instagram" width="30">
        </a>
    </header>
    <div class="container">
        <img src="instagram_bild_links.jpg" alt="Instagram Bild" width="200">
        <div class="image-placeholder">Feld 1</div>
        <div class="image-placeholder">Feld 2</div>
        <div class="image-placeholder">Feld 3</div>
        <img src="instagram_bild_rechts.jpg" alt="Instagram Bild" width="200">
    </div>
    <div class="footer">
        <p>Jasmin Frölke - Email: Jasminfroelke@gmx.de</p>
        <iframe 
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2686639.853694693!2d7.418682516406436!3d48.535496448273446!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4791e828c6e9b9b3%3A0x41c63f563e9815a8!2sSchwarzwald!5e0!3m2!1sde!2sde!4v1619505672437!5m2!1sde!2sde" 
            allowfullscreen>
        </iframe>
    </div>
</body>
</html>
