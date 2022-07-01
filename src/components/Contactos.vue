<template>
  <div id="contacto">
    <div class="footer-dark text-center">
      <a href="#"><img src="iconos/boton.png" alt="boton" /></a>
      <footer>
        <div class="container text-center">
          <div class="row">
            <div class="item text">
              <div class="col item social p-5">
                <a href="https://github.com/Jasmina-Santander"
                  ><img src="iconos/github.png" alt="github" /></a
                ><a href="https://www.linkedin.com/in/jasmina-santander-rojas/"
                  ><img src="iconos/linkedin.png" alt="linkedin"
                /></a>
              </div>
              <h3 class="titulo4 pt-2">Contactame y trabajemos juntos</h3>
              <p class="copyright">Jasmina Santander © 2022</p>
            </div>
          </div>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Quicksand&display=swap");

* {
  letter-spacing: 1px;
  font-family: "Quicksand", sans-serif;
}
.footer-dark {
  padding-top: 30px;
  color: #f0f9ff;
  background: linear-gradient(40deg, #4161b1, #368a4a, #235185);
  background-size: 400% 400%;
  position: relative;
  animation: cambiar 13s ease-in-out infinite;
}
@keyframes cambiar {
  0% {
    background-position: 0 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0 50%;
  }
}

.footer-dark h3 {
  margin-top: 0;
  font-weight: bold;
  font-size: 16px;
}

@media (max-width: 767px) {
  .footer-dark .item:not(.social) {
    text-align: center;
    padding-bottom: 20px;
  }
}

.footer-dark .item.text {
  margin-bottom: 36px;
}

@media (max-width: 767px) {
  .footer-dark .item.text {
    margin-bottom: 0;
  }
}

.footer-dark .item.text p {
  opacity: 0.6;
  margin-bottom: 0;
}

.footer-dark .item.social {
  text-align: center;
}

@media (max-width: 991px) {
  .footer-dark .item.social {
    text-align: center;
    margin-top: 20px;
  }
}

.footer-dark .item.social > a {
  font-size: 20px;
  width: 36px;
  height: 36px;
  line-height: 36px;
  display: inline-block;
  text-align: center;
  margin: 0 8px;
  color: #fff;
  opacity: 0.75;
}

.footer-dark .item.social > a:hover {
  opacity: 0.9;
}

.footer-dark .copyright {
  text-align: center;
  opacity: 0.3;
  font-size: 16px;
  margin-bottom: 0;
}

img {
  width: 50px;
  height: 50px;
}
</style>
