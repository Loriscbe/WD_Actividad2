<template>
  <div>

    <h1 class="pb-2">
     <icons :icon="['fas', 'star']" /> 
      Tipos de plano y ángulos de cámara. 
     <icons :icon="['fas', 'star']" /> 
     </h1>  
      <p>Nuestra escuela : <b-link href="http://www.graudissenydigitalitec.udl.cat/">Grado Diseño Digital y Tecnologías Creativas</b-link>.</p>

    <div>
      <b-embed
        type="iframe"
        aspect="16by9"
        src="https://www.youtube.com/embed/S5MH3srlu28"
        allowfullscreen
      ></b-embed>
    </div>

 </div>

</template>

<script>


export default {
  props: {  
   name: {
      type: String,
      default: 'AL DETALLE'
    }
  }
}
</script>



