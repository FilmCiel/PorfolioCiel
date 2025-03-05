<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Portafolio de Videos</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f9f9f9;
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
    }
    header {
      text-align: center;
      margin-bottom: 20px;
    }
    header h1 {
      font-size: 2.5rem;
      color: #555;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      width: 100%;
      max-width: 1200px;
    }
    .video {
      background: white;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      overflow: hidden;
    }
    iframe {
      width: 100%;
      height: 200px;
      border: none;
    }
    footer {
      margin-top: 20px;
      text-align: center;
      color: #777;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mi Portafolio</h1>
    <p>Bienvenido a mi espacio creativo.</p>
  </header>

  <section class="gallery">
    <div class="video">
      <iframe src="https://vimeo.com/1060237821/65583fa89f" allowfullscreen></iframe>
      <p>Video 1: Breve descripción aquí.</p>
    </div>
    <div class="video">
      <iframe src="https://www.youtube.com/embed/TU_VIDEO_2" allowfullscreen></iframe>
      <p>Video 2: Breve descripción aquí.</p>
    </div>
  </section>

  <footer>
    <p>© 2025 - Mi Portafolio | Contacto: <a href="mailto:tucorreo@example.com">tucorreo@example.com</a></p>
  </footer>
</body>
</html>
