# primertarea
pagina web curriculum
mi primer tarea multiplataforma
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            background: #444;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenido a Mi Página</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
    <section id="inicio">
        <h2>Inicio</h2>
        <p>Esta es una página de ejemplo siguiendo buenas prácticas de diseño web.</p>
    </section>
    <section id="sobre">
        <h2>Sobre Nosotros</h2>
        <p>Información sobre el contenido de la página y su propósito.</p>
    </section>
    <section id="contacto">
        <h2>Contacto</h2>
        <p>Puedes contactarnos en <strong>email@ejemplo.com</strong></p>
    </section>
    <footer>
        <p>&copy; 2025 - Todos los derechos reservados</p>
    </footer>
</body>
</html>

