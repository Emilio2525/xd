<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>STAR STUDIOS - Impulsando Talento</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        /* GENERAL */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
            scroll-behavior: smooth;
        }

        body {
            background-color: #f5f5f5;
            color: #333;
        }

        /* NAVBAR */
        header {
            background-color: white;
            padding: 15px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: #1a237e;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 30px;
        }

        nav a {
            text-decoration: none;
            color: #1a237e;
            font-weight: bold;
            transition: 0.3s;
        }

        nav a:hover {
            color: #FFD700;
        }

        /* HERO SECTION */
        .hero {
            height: 100vh;
            background: linear-gradient(rgba(20, 20, 20, 0.6), rgba(20, 20, 20, 0.6)), 
                        url('https://source.unsplash.com/1600x900/?music,studio') center/cover no-repeat;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            padding: 20px;
        }

        .hero h1 {
            font-size: 4rem;
            margin-bottom: 15px;
            animation: fadeIn 1.5s ease-in-out;
        }

        .hero p {
            font-size: 1.6rem;
            max-width: 800px;
            margin: auto;
            animation: fadeIn 2s ease-in-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* SECCIONES */
        section {
            padding: 100px 10%;
            text-align: center;
        }

        .info-section {
            background: white;
            padding: 50px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            max-width: 900px;
            margin: 40px auto;
            text-align: left;
        }

        .info-section h2 {
            color: #1a237e;
            font-size: 2rem;
            margin-bottom: 15px;
        }

        .info-section p {
            font-size: 1.2rem;
            line-height: 1.8;
        }

        .info-section ul {
            margin-top: 10px;
            padding-left: 20px;
        }

        /* FOOTER */
        footer {
            background-color: #1a237e;
            padding: 20px;
            text-align: center;
            color: white;
            margin-top: 50px;
        }

        /* BOTÓN ANIMADO */
        .cta-button {
            display: inline-block;
            padding: 15px 30px;
            margin-top: 20px;
            background: #FFD700;
            color: #1a237e;
            font-size: 1.2rem;
            font-weight: bold;
            border-radius: 5px;
            text-decoration: none;
            transition: 0.3s;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
        }

        .cta-button:hover {
            background: #1a237e;
            color: white;
            transform: scale(1.05);
        }

    </style>
</head>
<body>

    <!-- Navbar -->
    <header>
        <div class="logo">STAR STUDIOS</div>
        <nav>
            <ul>
                <li><a href="#nosotros">Quiénes Somos</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div>
            <h1>Impulsamos el Talento al Siguiente Nivel</h1>
            <p>La disquera y casa productora que apoya a los artistas independientes para que logren su máximo potencial.</p>
        </div>
    </section>

    <!-- Quiénes Somos -->
    <section id="nosotros">
        <div class="info-section">
            <h2>¿Qué es STAR STUDIOS?</h2>
            <p>Somos una disquera, casa animadora y editorial que impulsa el talento de artistas independientes que buscan darse a conocer en la industria. Brindamos apoyo financiero y publicitario a cambio de un porcentaje de sus ganancias.</p>
            
            <h2>Misión</h2>
            <p>Nuestra misión es apoyar a talentos emergentes, ayudándolos a expandir sus carreras musicales y a llegar a un público más amplio.</p>

            <h2>Visión</h2>
            <p>Aspiramos a ser la empresa líder en producción artística, brindando oportunidades a artistas de todo el mundo para que alcancen el reconocimiento que merecen.</p>

            <h2>Competencia</h2>
            <p>Nuestros principales competidores en la industria son:</p>
            <ul>
                <li>Rancho Humilde</li>
                <li>Universal Music</li>
                <li>Warner Music</li>
                <li>Bandai Namco</li>
            </ul>
        </div>
    </section>

    <!-- Contacto -->
    <section id="contacto">
        <h2>Contáctanos</h2>
        <p>Si eres un artista y quieres formar parte de STAR STUDIOS, envíanos un mensaje.</p>
        <a href="mailto:contacto@starstudios.com" class="cta-button">Enviar Correo</a>
    </section>

    <footer>
        <p>&copy; 2025 STAR STUDIOS - Todos los derechos reservados.</p>
    </footer>

</body>
</html>
