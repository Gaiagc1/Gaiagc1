<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CUFCAP - Centro Universitario de Formación</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f8f8f8;
        }
        header {
            background-color: #6A1B9A;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            font-size: 1.2rem;
        }
        nav {
            background-color: #4A148C;
            display: flex;
            justify-content: center;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 40px;
            background-color: white;
            margin: 20px auto;
            border-radius: 10px;
            max-width: 1200px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        section h2 {
            color: #6A1B9A;
        }
        .programs {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .program {
            background-color: #f3e5f5;
            border-radius: 10px;
            padding: 20px;
            text-align: center;
            width: 250px;
        }
        footer {
            background-color: #4A148C;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>
    <h1>CUFCAP</h1>
    <p>Creando los futuros líderes de México</p>
</header>

<nav>
    <a href="#about">Quiénes Somos</a>
    <a href="#programs">Programas</a>
    <a href="#testimonials">Testimonios</a>
    <a href="#contact">Contacto</a>
</nav>

<section id="about">
    <h2>Quiénes Somos</h2>
    <p>En CUFCAP nos enfocamos en formar profesionales preparados para afrontar los retos globales del futuro. Nuestra misión es brindar una educación de excelencia que fomente el desarrollo integral de nuestros estudiantes.</p>
    <h3>Misión:</h3>
    <p>Formar a los futuros líderes de México a través de una educación de excelencia en áreas clave como tecnología, idiomas e innovación.</p>
    <h3>Visión:</h3>
    <p>Ser un referente educativo que forme líderes capaces de transformar su entorno, promoviendo una cultura de excelencia, innovación y compromiso social.</p>
</section>

<section id="programs">
    <h2>Programas Académicos</h2>
    <div class="programs">
        <div class="program">
            <h3>Licenciaturas</h3>
            <p>Programas que desarrollan las habilidades necesarias para triunfar en el mundo laboral.</p>
        </div>
        <div class="program">
            <h3>Maestrías</h3>
            <p>Especialízate en tu área de interés y expande tus horizontes profesionales.</p>
        </div>
        <div class="program">
            <h3>Cursos de Idiomas</h3>
            <p>Aprende japonés e inglés con nuestros expertos.</p>
        </div>
        <div class="program">
            <h3>Regularizaciones</h3>
            <p>Prepárate para tus exámenes y asegura tu éxito académico.</p>
        </div>
    </div>
</section>

<section id="testimonials">
    <h2>Testimonios</h2>
    <p>"Estudiar en CUFCAP ha sido la mejor decisión de mi vida. Gracias a sus programas, ahora estoy preparado para enfrentar los desafíos del mundo laboral." - Juan P.</p>
</section>

<section id="contact">
    <h2>Contacto</h2>
    <form>
        <label for="name">Nombre:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        <label for="email">Correo Electrónico:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        <label for="message">Mensaje:</label><br>
        <textarea id="message" name="message" rows="5" required></textarea><br><br>
        <button type="submit">Enviar Mensaje</button>
    </form>
</section>

<footer>
    <p>CUFCAP &copy; 2024. Todos los derechos reservados.</p>
</footer>

</body>
</html>
