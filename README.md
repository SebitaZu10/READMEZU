<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sobre mí - Programador</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Roboto', sans-serif;
      background-color: #f2f4f8;
      color: #333;
      line-height: 1.6;
    }

    header {
      background-color: #0a192f;
      color: #fff;
      padding: 3rem 1rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
      color: #a8b2d1;
    }

    .container {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 0 1rem;
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    .profile-img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      margin: 2rem auto;
      display: block;
      border: 4px solid #0a192f;
    }

    .section {
      padding: 2rem;
    }

    .section h2 {
      color: #0a192f;
      margin-bottom: 1rem;
      border-bottom: 2px solid #0a192f;
      display: inline-block;
    }

    ul.skills {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-top: 1rem;
    }

    ul.skills li {
      background-color: #e0e0e0;
      padding: 0.5rem 1rem;
      border-radius: 20px;
      font-weight: bold;
    }

    .projects a {
      display: block;
      color: #007acc;
      margin: 0.5rem 0;
      text-decoration: none;
      transition: all 0.3s ease;
    }

    .projects a:hover {
      color: #005f99;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #0a192f;
      color: #fff;
      margin-top: 2rem;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }

      .section {
        padding: 1rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Tu Nombre</h1>
    <p>Desarrollador Web | Full Stack | Apasionado por la tecnología</p>
  </header>

  <div class="container">
    <img src="https://via.placeholder.com/150" alt="Foto de perfil" class="profile-img" />

    <section class="section">
      <h2>Sobre mí</h2>
      <p>
        ¡Hola! Soy un desarrollador web con experiencia en el desarrollo de aplicaciones modernas,
        tanto del lado del cliente como del servidor. Me encanta construir soluciones que tengan un impacto real,
        y siempre estoy buscando aprender nuevas tecnologías y mejorar mis habilidades.
      </p>
    </section>

    <section class="section">
      <h2>Habilidades</h2>
      <ul class="skills">
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>React</li>
        <li>Node.js</li>
        <li>Git</li>
        <li>MongoDB</li>
        <li>MySQL</li>
        <li>Python</li>
      </ul>
    </section>

    <section class="section projects">
      <h2>Proyectos destacados</h2>
      <a href="https://github.com/tuusuario/proyecto1" target="_blank">🧠 Proyecto 1 - Descripción corta</a>
      <a href="https://github.com/tuusuario/proyecto2" target="_blank">📱 Proyecto 2 - Descripción corta</a>
      <a href="https://github.com/tuusuario/proyecto3" target="_blank">💻 Proyecto 3 - Descripción corta</a>
    </section>

    <section class="section">
      <h2>Contacto</h2>
      <p>Email: tuemail@ejemplo.com</p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/tuusuario" target="_blank">linkedin.com/in/tuusuario</a></p>
      <p>GitHub: <a href="https://github.com/tuusuario" target="_blank">github.com/tuusuario</a></p>
    </section>
  </div>

  <footer>
    © 2025 Tu Nombre | Todos los derechos reservados
  </footer>

</body>
</html>
