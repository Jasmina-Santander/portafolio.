<template>
  <div id="proyectos">
    <div class="fondo3">
      <div class="container text-center pt-5 pb-5">
        <h2 class="titulo3 mb-4 mt-4">Proyectos</h2>
<!--Imagenes de proyectos-->
   <div class="row justify-content-center">
        <div class="imagenes col-12 col-sm-7 m-3 shadow-lg ">
          

          <div class="c-img">
            <img class="imagen img-fluid" src="img/python1.png" alt="django" />
            <!--enlace-->
            <div class="botonenlace">
              <a href="http://18.229.123.232/main" class="enlace">Django
                <button type="button" class="btn btn-outline-info">
                  Ver proyecto
                </button></a>
            </div>
          </div>

          <div class="c-img">
            <img class="imagen img-fluid" src="img/peliculas.png" alt="api" />
               <!--enlace-->
            <div class="botonenlace">
              <a href="https://github.com/Jasmina-Santander/Api_peliculas" class="enlace">Vue
                <button type="button" class="btn btn-outline-info">
                  Ver proyecto
                </button></a>
            </div>
          </div>

          <div class="c-img">
            <img class="imagen img-fluid" src="img/blog.png" alt="routerVue" />
               <!--enlace-->
            <div class="botonenlace">
              <a href="https://github.com/Jasmina-Santander/vue_blogRouter"
                class="enlace">Vue
                <button type="button" class="btn btn-outline-info">
                  Ver proyecto
                </button></a>
            </div>
          </div>

          <div class="c-img">
            <img class="imagen img-fluid" src="img/Tecnochile.png" alt="sass y javascript"/>
               <!--enlace-->
            <div class="botonenlace">
              <a href="https://github.com/Jasmina-Santander/Techno_chile" class="enlace">Sass
                <button type="button" class="btn btn-outline-info">
                  Ver proyecto
                </button></a>
            </div>
          </div>

          <div class="c-img">
            <img class="imagen img-fluid" src="img/floreria.png" alt="sass" />
               <!--enlace-->
            <div class="botonenlace">
              <a href="https://github.com/Jasmina-Santander/floreria" class="enlace">Sass
                <button type="button" class="btn btn-outline-info">
                  Ver proyecto
                </button></a>
            </div>
          </div>

          <div class="c-img">
            <img class="imagen img-fluid" src="img/comunidadSostenible.png" alt="css"/>
               <!--enlace-->
            <div class="botonenlace">
              <a href="https://github.com/Jasmina-Santander/comunidad-sostenible" class="enlace">Css
                <button type="button" class="btn btn-outline-info">
                  Ver proyecto
                </button></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Quicksand&display=swap");

* {
  font-family: "Quicksand", sans-serif;
}
.fondo3 {
  color: rgb(36, 35, 35);
  background: #f2f2f5;

}
.titulo3 {
  font-size: 30pt;
  color: rgb(0, 0, 0);
  font-weight: bold;
}
.imagen {

  border: 1px solid rgb(0, 0, 0);
  align-items: center;
}
.imagenes {
  padding-bottom: 150px;
  padding-top: 100px;
  padding: 30px;
 
}

.botonenlace {
  position: absolute;
  top: 0;
  bottom: 0;
  width: 97%;
  height: 93.5%;
  background: linear-gradient(40deg, #4161b1, #368a4a, #235185);
  color: rgb(0, 0, 0);
  font-size: 12pt;
  text-decoration: none;
  border: 1px solid #000000;
  visibility: hidden;
  margin-top: 10px;
  border-color: #3498db;
  color: #fff;
  box-shadow: 0 0 40px 40px #3498db inset, 0 0 0 0 #3498db;
  -webkit-transition: all 150ms ease-in-out;
  transition: all 150ms ease-in-out;
  align-items: center;
}
.botonenlace:hover {
  box-shadow: 0 0 10px 0 #3498db inset, 0 0 10px 4px #3498db;
}
.enlace {
  font-size: 35pt;
  color: rgb(233, 233, 233);
  position: absolute;
  top: 10;
  left: 0;
}
.c-img {
  position: relative;
  display: inline-flex;
  align-items: center;
  transition: ease-in;
  padding: 10px;
}
.c-img:hover > .botonenlace {
  opacity: 1;
  visibility: visible;
}
.btn-outline-info {
  color: #fff;
}
</style>
