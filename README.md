<!doctype html>
<html lang="es">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Portafolio | Aldair Restrepo</title>
    <meta name="description" content="Portafolio de Aldair Restrepo: proyectos y desarrollos." />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="assets/css/styles.css" />
  </head>
  <body>
    <header class="site-header">
      <div class="container header-inner">
        <div class="brand">
          <span class="brand-name">Aldair Restrepo</span>
          <span class="brand-role">Desarrollador</span>
        </div>
        <nav class="nav">
          <a href="#sobre-mi">Sobre mí</a>
          <a href="#habilidades">Habilidades</a>
          <a href="#proyectos">Proyectos</a>
          <a href="#contacto">Contacto</a>
        </nav>
      </div>
    </header>

    <main>
      <section class="hero">
        <div class="container hero-inner">
          <h1>Hola, soy Aldair 👋</h1>
          <p>
            Construyo soluciones web y comparto aquí los proyectos que he ido
            desarrollando. Este portafolio está pensado para correr en XAMPP
            (Apache), por lo que es 100% estático y fácil de desplegar.
          </p>
          <div class="hero-cta">
            <a class="btn primary" href="#proyectos">Ver proyectos</a>
            <a class="btn" href="#contacto">Contactar</a>
          </div>
        </div>
      </section>

      <section id="sobre-mi" class="section">
        <div class="container">
          <h2>Sobre mí</h2>
          <p>
            Desarrollador con enfoque en aplicaciones web. Me gusta escribir
            código claro, mantener buenas prácticas y aprender tecnologías que
            faciliten entregar valor rápido.
          </p>
        </div>
      </section>

      <section id="habilidades" class="section">
        <div class="container">
          <h2>Habilidades</h2>
          <p>Estas son las tecnologías con las que trabajo:</p>
          <div id="skills-list" class="tags" aria-live="polite"></div>
        </div>
      </section>

      <section id="proyectos" class="section">
        <div class="container">
          <h2>Proyectos</h2>
          <div id="projects-grid" class="projects-grid" aria-live="polite"></div>
        </div>
      </section>

      <section id="contacto" class="section">
        <div class="container">
          <h2>Contacto</h2>
          <p>
            ¿Tienes una idea o quieres colaborar? Escríbeme:
            <a href="mailto:aldair.restrepo@example.com">aldarestrepo6@gmail.com</a>
          </p>
          <div class="social">
            <a href="#" aria-label="GitHub" title="GitHub">GitHub</a>
            <a href="https://www.linkedin.com/in/elian-restrepo/" target="_blank" rel="noopener" aria-label="LinkedIn" title="LinkedIn">LinkedIn</a>
          </div>
        </div>
      </section>
    </main>

    <footer class="site-footer">
      <div class="container">
        <small>© <span id="year"></span> Aldair Restrepo. Todos los derechos reservados.</small>
      </div>
    </footer>

    <script src="assets/js/main.js"></script>
  </body>
  </html>
