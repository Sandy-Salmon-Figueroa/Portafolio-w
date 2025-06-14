<!-- Estructura base del portafolio profesional -->
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Portafolio Profesional</title>
  <link rel="stylesheet" href="./css/styles.css">
  <script defer src="./js/scripts.js"></script>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>

  <!-- Sección: Inicio -->
  <section id="inicio" class="text-center p-5 bg-primary text-white">
    <img src="Sandy Salmon" alt="Foto de perfil" class="rounded-circle mb-3" width="150">
    <h1>Hola, soy Sandy Salmon</h1>
    <p>Desarrollador Web | Diseñador UI/UX</p>
  </section>

  <!-- Sección: Sobre mí -->
  <section id="sobremi" class="container py-5">
    <h2 class="text-center">Sobre mí</h2>
    <p class="text-center">Soy una persona muy apasionada por la tecnología, me encanta aprender cada día sobre este mundo, próxima a graduarme como ingeniera en Tecnologías de la Información.</p>
  </section>

  <!-- Sección: Portafolio -->
  <section id="portafolio" class="container py-5">
    <h2 class="text-center">Mis Proyectos</h2>
    <div class="row">
      <!-- Proyecto 1 -->
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="./assets/proyecto1.jpg" class="card-img-top" alt="Proyecto 1">
          <div class="card-body">
            <h5 class="card-title">Proyecto 1</h5>
            <p class="card-text">Descripción breve del proyecto.</p>
            <a href="#" class="btn btn-primary">Ver más</a>
          </div>
        </div>
      </div>
      <!-- Puedes duplicar bloques similares para más proyectos -->
    </div>
  </section>

  <!-- Sección: Habilidades -->
  <section id="habilidades" class="bg-light py-5">
    <div class="container">
      <h2 class="text-center">Habilidades</h2>
      <ul class="list-group list-group-flush">
        <li class="list-group-item">HTML5, CSS3, JavaScript</li>
        <li class="list-group-item">React, Bootstrap, Tailwind</li>
        <li class="list-group-item">Diseño UI/UX con Figma</li>
        <li class="list-group-item">Git y GitHub</li>
      </ul>
    </div>
  </section>

  <!-- Sección: Contacto -->
  <section id="contacto" class="container py-5">
    <h2 class="text-center">Contáctame</h2>
    <form action="https://formspree.io/f/tu-id" method="POST" class="w-75 mx-auto">
      <div class="mb-3">
        <label for="nombre" class="form-label">Nombre</label>
        <input type="text" name="nombre" class="form-control" required>
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">Correo electrónico</label>
        <input type="email" name="email" class="form-control" required>
      </div>
      <div class="mb-3">
        <label for="mensaje" class="form-label">Mensaje</label>
        <textarea name="mensaje" rows="4" class="form-control" required></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Enviar</button>
    </form>
  </section>

  <footer class="text-center py-4 bg-dark text-white">
    <p>Sígueme en:
      <a href="https://github.com/sandysalmon" target="_blank" class="text-white mx-2"><i class="fab fa-github"></i></a>
      <a href="https://linkedin.com/in/sandysalmon" target="_blank" class="text-white mx-2"><i class="fab fa-linkedin"></i></a>
    </p>
    <p>&copy; 2025 Sandy Salmon</p>
  </footer>

</body>
</html>
