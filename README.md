# index.html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HardAdvisor AI</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #f8f9fa;
      color: #333;
    }
    header {
      background-color: #0d6efd;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    section {
      padding: 4rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    .feature {
      background-color: white;
      border-radius: 12px;
      padding: 2rem;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      text-align: center;
    }
    .feature i {
      font-size: 2rem;
      color: #0d6efd;
      margin-bottom: 1rem;
    }
    .cta {
      text-align: center;
      margin-top: 3rem;
    }
    .cta a {
      background-color: #0d6efd;
      color: white;
      padding: 1rem 2rem;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: background-color 0.3s;
    }
    .cta a:hover {
      background-color: #0b5ed7;
    }
    footer {
      background-color: #212529;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 4rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>HardAdvisor AI</h1>
    <p>Optimiza tu PC con inteligencia artificial</p>
  </header>

  <section>
    <h2>¿Qué es HardAdvisor AI?</h2>
    <p>HardAdvisor AI analiza el rendimiento de tu hardware en tiempo real, detecta cuellos de botella y te recomienda mejoras inteligentes adaptadas a tus juegos o software habitual.</p>

    <div class="features">
      <div class="feature">
        <i class="fas fa-microchip"></i>
        <h3>Monitoreo en tiempo real</h3>
        <p>Conoce el uso actual de tu CPU, RAM y GPU con reportes claros y detallados.</p>
      </div>
      <div class="feature">
        <i class="fas fa-brain"></i>
        <h3>IA inteligente</h3>
        <p>Nuestra IA analiza tus patrones y recomienda hardware basado en lo que realmente necesitas.</p>
      </div>
      <div class="feature">
        <i class="fas fa-gamepad"></i>
        <h3>Optimizado para gaming</h3>
        <p>Detecta limitaciones que afectan tus FPS y recibe sugerencias de mejora precisas.</p>
      </div>
    </div>

    <div class="cta">
      <a href="#">Descargar versión beta</a>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 HardAdvisor AI. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
