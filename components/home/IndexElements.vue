<template>
  <div>
     <!-- Banner principal -->
    <section class="main-banner section-container">
      <div class="content-wrapper content">
        <div class="container">
          <h1 class="title">Bienvenidos a Treemagazin</h1>
          <p class="subtitle">Toma el control de las métricas financieras de tu negocio y convierte el crecimiento sostenido en una realidad</p>
          <div>
            <a class="button white" href="/registrarme">Solicitar acceso temprano</a>
          </div>
        </div>
        <div class="container">
          <img class="image" src="~assets/images/computer.svg" alt="Computadora EDsoft">
        </div>
      </div>
    </section>

    <!-- Nuestros servicios -->
    <section class="services-section section-container">
      <h2>Nuestros servicios</h2>
      <div class="content-wrapper">
        <article class="service-item">
          <span class="jam jam-lightbulb"></span>
          <h3>Inteligencia de negocios</h3>
          <p>Saca a flote el maximo potencial de tu negocio con las herramientas de Business Intelligence</p>
        </article>
        <article class="service-item">
          <span class="jam jam-calculator"></span>
          <h3>Contabilidad inteligente</h3>
          <p>Contabilidad con superpoderes, las herramientas mas potentes para gestión tributaria.</p>
        </article>
        <article class="service-item">
          <span class="jam jam-tools"></span>
          <h3>Herramientas de productividad</h3>
          <p>Enfócate en lo importante y mejora el desempeño de tu equipo.</p>
        </article>
      </div>
    </section>

    <!-- Sobre nosotros -->
    <section class="section-container about-section">
      <div class="content-wrapper">
        <h2 class="title">Sobre nosotros</h2>
        <p>Nos apasiona ayudarte a alcanzar tus objetivos, conocenos.</p>
        <a href="/sobre-nosotros" class="button white ghost">Ver experiencia</a>
      </div>
      <img class="background" src="~assets/images/bg-section.jpg" alt="Alumnos estudiando">
    </section>

    <!-- Ultimos proyectos -->
    <section class="section-container last-projects">
      <h2>Casos de éxito</h2>
      <div class="content-wrapper">
        <a href="#" class="project-item">
          <article>
            <div>
              <h4>Proximamente</h4>
              <p>Descripción proyecto</p>
            </div>
            <div class="image-container">
              <img src="~assets/images/project-1.jpg" alt="Proyecto 1">
            </div>
          </article>
        </a>
        <a href="#" class="project-item">
          <article>
            <div>
              <h4>Proximamente</h4>
              <p>Descripción proyecto</p>
            </div>
            <div class="image-container">
              <img src="~assets/images/project-2.jpg" alt="Proyecto 2">
            </div>
          </article>
        </a>
        <a href="#" class="project-item">
          <article>
            <div>
              <h4>Proximamente</h4>
              <p>Descripción proyecto</p>
            </div>
            <div class="image-container">
              <img src="~assets/images/project-3.jpg" alt="Proyecto 3">
            </div>
          </article>
        </a>
        <a href="#" class="project-item">
          <article>
            <div>
              <h4>Proximamente</h4>
              <p>Descripción proyecto</p>
            </div>
            <div class="image-container">
              <img src="~assets/images/project-4.jpg" alt="Proyecto 4">
            </div>
          </article>
        </a>
      </div>
    </section>

    <!--  Trabajar con nosotros  -->
    <section class="work-with-us">
      <div class="content-wrapper">
        <h2 class="title">¿Quieres trabajar con nosotros?</h2>
        <p class="subtitle">Es momento de que tomes el control de tus finanzas <br/> registrate gratis y conoce los beneficios que tenemos para tí</p>
       
        <a href="/registrarme" class="button">Solicitar acceso temprano</a>
        
        <div class="social-networks">
          <a href="#" target="_blank"><span class="jam jam-facebook"></span></a>
          <a href="#" target="_blank"><span class="jam jam-twitter"></span></a>
          <a href="#" target="_blank"><span class="jam jam-whatsapp"></span></a>
          <a href="#" target="_blank"><span class="jam jam-instagram"></span></a>
        </div>
      </div>
    </section>
        
    <footer class="main-footer">
        <p>Todos los derechos reservados © 2020 | Treemagazin research technology</p>
    </footer>
  </div>
</template>

<script>
    export default {
        name:"IndexElements",
       
    }
</script>
