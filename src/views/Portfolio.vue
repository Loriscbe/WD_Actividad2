<template>
  <div class="portfolio">
    <h1>Ejemplos de fotos</h1>
    <Diapos/>
 </div>
</template>

<script>
import Diapos from '../components/Diapos.vue' 

export default {
   name: 'portfolio',
   components: {
        Diapos
  }
}
</script>

<style scoped>
.borde-rojo{
  border: 1px solid red;

}
.borde-azul{
  border: 1px solid blue;
}

</style>