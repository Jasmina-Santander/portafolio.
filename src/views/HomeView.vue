<template>
<div>
    <PrimeraVista />
  <Menu />
     <SobreMi />
         <Proyectos />
                  <Contactos />


</div>
</template>

<script>
import Contactos from '../components/Contactos.vue'
import Proyectos from '../components/Proyectos.vue'
import SobreMi from '../components/SobreMi.vue'
import Menu from '../components/Menu.vue'
import PrimeraVista from '../components/PrimeraVista.vue'
export default {
  name:"HomeView",
  components: {
   PrimeraVista,
   Menu,
   SobreMi,
   Proyectos,
    Contactos
  }
}
</script>

<style>

</style>
