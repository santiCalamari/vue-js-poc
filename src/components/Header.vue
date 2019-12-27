<template>
  <header>

     <nav class="navbar navbar-expand-md navbar-light mb-4">
      <a class="navbar-brand text-uppercase" href="#">Inicio</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <ul class="navbar-nav mr-auto">
            <li class="nav-item">
              <a class="nav-link text-uppercase" href="#">Nosotros <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle .color-text-nav text-uppercase" href="#" id="dropdown01" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Industria</a>
              <div class="dropdown-menu" aria-labelledby="dropdown01">
                <a class="dropdown-item" href="#">Industria 1</a>
                <a class="dropdown-item" href="#">Industria 2</a>
                <a class="dropdown-item" href="#">Industria 3</a>
              </div>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle .color-text-nav text-uppercase" href="#" id="dropdown01" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Productos</a>
              <div class="dropdown-menu" aria-labelledby="dropdown01">
                <a class="dropdown-item" href="#">Productos 1</a>
                <a class="dropdown-item" href="#">Productos 2</a>
                <a class="dropdown-item" href="#">Productos 3</a>
              </div>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle .color-text-nav text-uppercase" href="#" id="dropdown01" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Media</a>
              <div class="dropdown-menu" aria-labelledby="dropdown01">
                <a class="dropdown-item" href="#">Media 1</a>
                <a class="dropdown-item" href="#">Media 2</a>
                <a class="dropdown-item" href="#">Media 3</a>
              </div>
            </li>
            <li class="nav-item">
              <a class="nav-link text-uppercase" href="#">Contactenos</a>
            </li>
          </ul>
          <a class="nav-link color-text-nav font-weight-bold" href="#">Ingresar</a>
          <a class="nav-link color-text-nav font-weight-bold" href="#">Buscar Oficina</a>  
        
      </div>
    </nav>
</header>
</template>

<script>
   export default{

   }
</script>

<style>
  .color-text-nav{
    color: #111111;
  }
</style>