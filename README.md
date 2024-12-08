<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil de Carlos Caballero</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            text-align: center;
            padding: 20px;
        }
        .title {
            font-size: 2.5rem;
            font-weight: bold;
            margin-bottom: 10px;
            color: #4a90e2;
        }
        .nickname {
            font-size: 4rem;
            font-weight: bold;
            color: #ef476f;
            margin: 10px 0;
        }
        .image {
            margin: 20px 0;
        }
        .image img {
            border-radius: 50%;
            max-width: 200px;
        }
        .subtitle {
            font-size: 1.5rem;
            margin-bottom: 20px;
        }
        .section {
            margin-top: 30px;
        }
        .section h2 {
            font-size: 1.8rem;
            color: #333;
        }
        .section ul {
            list-style: none;
            padding: 0;
        }
        .section ul li {
            font-size: 1.2rem;
            margin: 10px 0;
        }
        .technologies span {
            display: inline-block;
            background-color: #ddd;
            color: #000;
            padding: 5px 10px;
            margin: 5px;
            border-radius: 5px;
            font-weight: bold;
        }
        .contact a {
            color: #ef476f;
            text-decoration: none;
            font-size: 1.5rem;
            display: inline-block;
            margin: 10px 0;
        }
        .contact a:hover {
            text-decoration: underline;
        }
        .svg-container {
            margin-top: 40px;
        }
        .svg-container svg {
            width: 100%;
            max-width: 600px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Título -->
        <h1 class="title">Yo soy Carlos Caballero</h1>
        <h2 class="nickname">ItamiDev</h2>
        <!-- Imagen -->
        <div class="image">
            <img src="file:///C:/Users/Eduardo/Desktop/Twitch/Itami" alt="Carlos Caballero">
        </div>
        <p class="subtitle">Desarrollador de Software</p>

        <!-- Sobre mí -->
        <div class="section">
            <h2>💡 Sobre mí</h2>
            <ul>
                <li>🎯 Pasión: Desarrollo de software, diseño creativo y proyectos innovadores.</li>
                <li>🌱 Actualmente aprendiendo: Spring Boot, metodologías DevOps, y diseño avanzado de UI.</li>
                <li>💬 ¿Por qué colaborar conmigo? Soy un solucionador de problemas con un enfoque creativo, dispuesto a aprender y trabajar en equipo.</li>
                <li>🚀 Inspiración: Transformar ideas en soluciones tangibles y útiles.</li>
            </ul>
        </div>

        <!-- Tecnologías -->
        <div class="section technologies">
            <h2>🛠️ Tecnologías en uso</h2>
            <span>JavaScript (JS)</span>
            <span>C#</span>
            <span>Java</span>
            <span>HTML5</span>
            <span>CSS3</span>
            <span>PHP</span>
        </div>

        <!-- Estadísticas -->
        <div class="section">
            <h2>📊 Estadísticas</h2>
            <img src="https://github-readme-stats.vercel.app/api?username=ItamiDev&show_icons=true&theme=radical" alt="Estadísticas de GitHub">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ItamiDev&layout=compact&theme=radical" alt="Lenguajes más usados">
        </div>

        <!-- Contacto -->
        <div class="section contact">
            <h2>📧 Contáctame</h2>
            <a href="mailto:carlos.eduardo.caballero.ayarza@gmail.com">
                <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Gmail_Icon.png" alt="Gmail" width="30"> carlos.eduardo.caballero.ayarza@gmail.com
            </a>
        </div>

        <!-- SVG Animado -->
        <div class="svg-container">
            <h2>✨ Inspiración</h2>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 600 100" preserveAspectRatio="xMidYMid meet">
                <style>
                    .text {
                        font-family: Arial, sans-serif;
                        font-size: 24px;
                        fill: #ef476f;
                        animation: typing 3s steps(20, end), blink 0.5s step-end infinite alternate;
                    }
                    @keyframes typing {
                        from { width: 0 }
                        to { width: 100% }
                    }
                    @keyframes blink {
                        from, to { border-color: transparent }
                        50% { border-color: black }
                    }
                </style>
                <text class="text" x="50%" y="50%" dominant-baseline="middle" text-anchor="middle">
                    "Construyendo soluciones que inspiran."
                </text>
            </svg>
        </div>
    </div>
</body>
</html>

