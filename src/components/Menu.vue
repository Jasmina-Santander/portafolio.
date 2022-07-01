<template>
  <div id="menu">
    <nav class="navbar navbar-expand-lg navbar-dark navbar-default">
  <div class="container-fluid">
    <a class="navbar-brand" href="#"></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a class="nav-item nav-link active" href="#home">HOME</a>
          <a class="nav-item nav-link" href="#menu">ACERCA DE MI</a>
          <a class="nav-item nav-link" href="#proyectos">PROYECTOS</a>
          <a class="nav-item nav-link" href="#contacto">CONTACTO</a>
        </div>
          </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Quicksand&display=swap");


.navbar-default {
  background-color: #358a96;
}

.nav-item {
  color: rgb(255, 255, 255);
  font-size: 15pt;
  margin-left: 30px;
  font-family: "Quicksand", sans-serif;
  font-weight:  bolder;
}
.nav-item:hover {
  color: rgb(255, 255, 255);
}
</style>
