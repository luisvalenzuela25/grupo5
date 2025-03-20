<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PROYECTO DE INGENIERÍA | [Nombre del Proyecto]</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(45deg, #6a5acd, #ff6347);
      color: white;
      line-height: 1.6;
      padding: 20px;
    }

    header {
      text-align: center;
      padding: 50px 0;
      background: rgba(0, 0, 0, 0.4);
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
      margin-bottom: 40px;
    }

    header h1 {
      font-size: 3.5rem;
      font-weight: bold;
      text-transform: uppercase;
      letter-spacing: 3px;
      animation: fadeIn 2s ease-in-out;
    }

    header p {
      font-size: 1.2rem;
      font-style: italic;
      color: #ffcd00;
      margin-top: 10px;
    }

    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }

    section {
      margin: 20px auto;
      max-width: 1000px;
      background: rgba(255, 255, 255, 0.1);
      border-radius: 15px;
      padding: 40px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
      backdrop-filter: blur(5px);
      transition: all 0.3s ease;
    }

    section:hover {
      transform: scale(1.03);
    }

    h2 {
      color: #ff6347;
      font-size: 2.5rem;
      margin-bottom: 20px;
      text-transform: uppercase;
    }

    h3 {
      color: #fff;
      font-size: 1.8rem;
      margin-top: 30px;
    }

    p {
      font-size: 1.1rem;
      color: #f5f5f5;
      margin-bottom: 20px;
    }

    ul {
      list-style-type: none;
      padding: 0;
    }

    ul li {
      background: rgba(255, 255, 255, 0.2);
      margin-bottom: 12px;
      padding: 10px;
      border-radius: 8px;
      border: 2px solid #ff6347;
      transition: background-color 0.3s ease;
    }

    ul li:hover {
      background-color: rgba(255, 255, 255, 0.4);
    }

    a {
      text-decoration: none;
      color: #ffcd00;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    a:hover {
      color: #ff6347;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #1a1a1a;
      color: #ffcd00;
      margin-top: 40px;
      border-radius: 10px;
    }
  </style>
</head>
<body>

<header>
  <h1>[Nombre del Proyecto]</h1>
  <p>"Escribe una cita relevante o inspiradora para tu proyecto." (Autor)</p>
</header>

<section>
  <h2>Bienvenido a nuestro Proyecto</h2>
  <p>El grupo <strong>[Nombre del Grupo]</strong> les da la bienvenida a nuestro website, cuyo propósito es dar a conocer la documentación de nuestra trayectoria en el desarrollo de <span style="font-weight: bold; color: #ff6347;">[breve descripción del objetivo del proyecto]</span>. A través de esta página, podrás conocer más sobre nuestras ideas innovadoras y el impacto que buscamos generar en el ámbito de la ingeniería.</p>
</section>

<section>
  <h2>Tabla de contenidos</h2>
  <ul>
    <li><a href="#mision">Misión</a></li>
    <li><a href="#vision">Visión</a></li>
    <li><a href="#objetivos">Objetivos</a></li>
    <li><a href="#metodologia">Metodología</a></li>
    <li><a href="#quienes-somos">¿Quiénes somos?</a></li>
  </ul>
</section>

<section id="mision">
  <h2>Misión</h2>
  <p>Nuestra misión es <span style="font-weight: bold; color: #ff6347;">[explicar el propósito principal de tu proyecto]</span>. Buscamos <span style="font-weight: bold; color: #ff6347;">[beneficios o impacto]</span> a través de <span style="font-weight: bold; color: #ff6347;">[cómo planean lograrlo]</span>.</p>
</section>

<section id="vision">
  <h2>Visión</h2>
  <p>Nuestra visión es <span style="font-weight: bold; color: #ff6347;">[explicar lo que aspiran a lograr en el futuro con el proyecto]</span>. Queremos <span style="font-weight: bold; color: #ff6347;">[objetivo a largo plazo o meta]</span>. A través de <span style="font-weight: bold; color: #ff6347;">[métodos, tecnología o enfoques]</span>, buscamos <span style="font-weight: bold; color: #ff6347;">[impacto positivo]</span>.</p>
</section>

<section id="objetivos">
  <h2>Objetivos</h2>
  <h3>Objetivo General:</h3>
  <p><span style="font-weight: bold; color: #ff6347;">[Describe el objetivo principal de tu proyecto.]</span></p>
  
  <h3>Objetivos Específicos:</h3>
  <ul>
    <li>[Objetivo específico 1]</li>
    <li>[Objetivo específico 2]</li>
    <li>[Objetivo específico 3]</li>
  </ul>
</section>

<section id="metodologia">
  <h2>Metodología</h2>
  <p>[Explique la metodología o los pasos que seguirán para desarrollar el proyecto. Esto puede incluir el enfoque de investigación, las técnicas o herramientas que utilizarán, o cómo se organizarán.]</p>
</section>

<section id="quienes-somos">
  <h2>¿Quiénes somos?</h2>
  <ul>
    <li><strong>LUIS VALENZUELA</strong> – [Breve descripción de Luis, sus habilidades o rol en el proyecto]</li>
    <li><strong>KARLA ORDINOLA</strong> – [Breve descripción de Karla, sus habilidades o rol en el proyecto]</li>
    <li><strong>ELVIS PILCO</strong> – [Breve descripción de Elvis, sus habilidades o rol en el proyecto]</li>
  </ul>
</section>

<footer>
  <p>&copy; 2025 [Nombre del Proyecto]. Todos los derechos reservados.</p>
</footer>

</body>
</html>
