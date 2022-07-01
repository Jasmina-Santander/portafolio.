<template>
  <div id="home">
    <div class="fondo1">
      <div class="titulo1">
        <h1>
          Jasmina Santander
          <br />
          Desarrolladora Full-Stack
        </h1>
        <a href="#menu" class="btn btn1">Ver mas</a>
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
  padding: 0px;
  margin: 0px;
  font-family: "Quicksand", sans-serif;
}
.fondo1 {
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
  background: linear-gradient(40deg, #4161b1, #368a4a, #235185);
  background-size: 400% 400%;
  position: relative;
  animation: cambiar 9s ease-in-out infinite;
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
.titulo1 {
  text-align: center;
  align-items: center;
  font-size: medium;
  letter-spacing: 2px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  padding: 2rem 3rem;
  text-shadow: black 0.1em 0.1em 0.2em
}

.btn {
  position: relative;
  display: block;
  color: white;
  font-size: 12pt;
  text-decoration: none;
  margin: 30px 0;
  border: 2px solid #ffffff;
  padding: 14px 60px;
  text-transform: uppercase;
  overflow: hidden;
  transition: 1s all ease;
}
.btn::before {
  background-color: #55d0e0;
  content: "";
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: -1;
  transition: all 0.6s ease;
}

.btn1::before {
  width: 0%;
  height: 100%;
}

.btn1:hover::before {
  width: 100%;
}
</style>
