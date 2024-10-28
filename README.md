<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Personalización de Cascos</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <!-- Header -->
  <header class="header">
    <div class="container">
      <h1 class="logo">CascoPersonalizado</h1>
      <nav class="nav">
        <a href="#servicios">Servicios</a>
        <a href="#galeria">Galería</a>
        <a href="#proceso">Cómo Funciona</a>
        <a href="#contacto">Contacto</a>
        <a href="#cta" class="cta-btn">Personaliza tu Casco</a>
      </nav>
    </div>
  </header>

  <!-- Hero Image -->
  <section class="hero">
    <h2>Expresa tu estilo, lleva tu casco al siguiente nivel</h2>
    <p>Personalización de cascos para esquí, bicicleta y motocicleta con diseños y vinilos de alta calidad.</p>
    <a href="#cta" class="hero-btn">Empieza ahora</a>
  </section>

  <!-- Servicios -->
  <section id="servicios" class="servicios">
    <h2>Nuestros Servicios</h2>
    <div class="servicios-grid">
      <div class="servicio">
        <h3>Personalización de Cascos de Esquí</h3>
        <p>Diseños únicos y vinilos duraderos para destacar en la nieve.</p>
      </div>
      <div class="servicio">
        <h3>Personalización de Cascos de Bicicleta</h3>
        <p>Haz de tu casco de ciclismo una obra de arte personalizada.</p>
      </div>
      <div class="servicio">
        <h3>Personalización de Cascos de Motocicleta</h3>
        <p>Vinilos resistentes para un estilo único y seguro en la carretera.</p>
      </div>
    </div>
  </section>

  <!-- Galería -->
  <section id="galeria" class="galeria">
    <h2>Galería de Diseños</h2>
    <div class="galeria-grid">
      <img src="casco1.jpg" alt="Casco personalizado 1">
      <img src="casco2.jpg" alt="Casco personalizado 2">
      <img src="casco3.jpg" alt="Casco personalizado 3">
      <!-- Añadir más imágenes aquí -->
    </div>
  </section>

  <!-- Proceso de Personalización -->
  <section id="proceso" class="proceso">
    <h2>Cómo Funciona</h2>
    <div class="proceso-pasos">
      <div class="paso">
        <h3>1. Consulta Inicial</h3>
        <p>Conéctate con nosotros y cuéntanos tus ideas y preferencias.</p>
      </div>
      <div class="paso">
        <h3>2. Diseño y Aprobación</h3>
        <p>Recibe un diseño preliminar para su revisión y aprobación.</p>
      </div>
      <div class="paso">
        <h3>3. Aplicación de Vinilo</h3>
        <p>Aplicación de vinilos con alta precisión y calidad.</p>
      </div>
      <div class="paso">
        <h3>4. Entrega</h3>
        <p>Recibe tu casco personalizado en el menor tiempo posible.</p>
      </div>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="contacto">
    <h2>Contáctanos</h2>
    <form action="#" method="POST" class="contact-form">
      <input type="text" placeholder="Nombre" required>
      <input type="email" placeholder="Correo electrónico" required>
      <textarea placeholder="Describe tu diseño deseado..." required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <p>&copy; 2024 CascoPersonalizado. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
/* Reset de márgenes y paddings */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  color: #333;
}

.container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1rem 2rem;
}

.header {
  background-color: #222;
  color: #fff;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
}

.nav a {
  color: #fff;
  margin-left: 1rem;
  text-decoration: none;
}

.nav .cta-btn {
  background-color: #ff5722;
  padding: 0.5rem 1rem;
  border-radius: 5px;
}

.hero {
  text-align: center;
  padding: 5rem 1rem;
  background: url('hero-image.jpg') no-repeat center center / cover;
  color: #fff;
}

.hero h2 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 2rem;
}

.hero-btn {
  background-color: #ff5722;
  padding: 0.75rem 1.5rem;
  border-radius: 5px;
  color: #fff;
  text-decoration: none;
}

.servicios, .galeria, .proceso, .contacto {
  padding: 3rem 1rem;
  text-align: center;
}

.servicios-grid, .galeria-grid, .proceso-pasos {
  display: flex;
  gap: 1rem;
  justify-content: center;
}

.servicio, .paso {
  width: 250px;
  background-color: #f5f5f5;
  padding: 1rem;
  border-radius: 5px;
}

.galeria-grid img {
  width: 100%;
  border-radius: 5px;
}

.contact-form input, .contact-form textarea, .contact-form button {
  width: 100%;
  margin-bottom: 1rem;
  padding: 0.75rem;
  border-radius: 5px;
}

.footer {
  background-color: #222;
  color: #fff;
  text-align: center;
  padding: 1rem 0;
}
