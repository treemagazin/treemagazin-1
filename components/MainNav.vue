<template>
  <header class="main-header">
    <div class="content-wrapper">
      <a href="/">
        <img src="~/assets/treemagazin-logo.svg" alt="Logo EDsoft">
      </a>
      <span id="open-menu-button" class="jam jam-menu"></span>
      <nav id="main-menu" class="main-menu">
        <span id="close-menu-button" class="jam jam-close"></span>
        <ul>
          <li>
            <a href="/">Inicio</a>
          </li>
          <li>
            <a href="/quienes-somos">¿Quiénes somos?</a>
          </li>
          <li>
            <a href="/soluciones">Soluciones</a>
          </li>
          <li>
            <a href="/contacto">Contacto</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>

</template>

 <script>
    export default {
        name:"MainNav"
    }
 </script>
 