<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Responsiva</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 1rem;
            text-decoration: none;
        }
        main {
            padding: 1rem;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        @media (max-width: 600px) {
            nav {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenido a Mi Página Web</h1>
    </header>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#acerca">Acerca de</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <main>
        <section id="inicio">
            <h2>Inicio</h2>
            <p>Esta es la sección de inicio de la página web.</p>
        </section>
        <section id="acerca">
            <h2>Acerca de</h2>
            <p>Esta es la sección acerca de nosotros.</p>
        </section>
        <section id="contacto">
            <h2>Contacto</h2>
            <p>Esta es la sección de contacto.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Mi Página Web</p>
    </footer>
</body>
</html>
