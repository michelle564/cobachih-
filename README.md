<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .menu {
            text-align: center;
            margin-bottom: 20px;
        }
        .menu a {
            text-decoration: none;
            color: #333;
            padding: 5px 10px;
        }
        .menu a:hover {
            background-color: #ddd;
            border-radius: 5px;
        }
        .video-container {
            position: relative;
            padding-bottom: 56.25%;
            height: 0;
            overflow: hidden;
        }
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body>
    
    <header>
        <h1>Mi Página Web</h1>
    </header>
    <div class="container">
        <div class="menu">
            <a href="#">Inicio</a>
            <a href="#">Sobre Nosotros</a>
            <a href="#">Contacto</a>
        </div>
        <h2>¡Te doy una gran bienvenida a mi página web!</h2>
        <p>Contenido de la página...</p>
        <div class="video-container">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
        </div>
        <table>
            <tr>
                <th>Encabezado 1</th>
                <th>Encabezado 2</th>
            </tr>
            <tr>
                <td>Dato 1</td>
                <td>Dato 2</td>
            </tr>
        </table>
        <marquee>¡Este es un texto de marquesina!</marquee>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d387282.5682228117!2d-74.2598654667969!3d40.69714942273001!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c250d9c7c737c9%3A0x6aef4a38555b7a27!2sNew%20York%2C%20EE.%20UU.!5e0!3m2!1ses!2ses!4v1617796201756!5m2!1ses!2ses" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </div>
</body>
</html>
