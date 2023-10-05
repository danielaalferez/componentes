<template>
  <div>
    <button @click="verContenido" v-if="!contenidoVisible">{{ buttonText }}</button>
    <button @click="verContenido" v-else>{{ buttonTextVisible }}</button>
    <div v-if="contenidoVisible">
      La perseverancia y la dedicación son valores que se reflejan en el fútbol sala femenino, donde el esfuerzo constante lleva al éxito
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return { 
      buttonText: 'Ver contenido',
      buttonTextVisible: 'Ocultar contenido',
      contenidoVisible: true
    };
  },
  methods: {
    verContenido() {
    
      this.contenidoVisible = !this.contenidoVisible;
      
     
      this.buttonText = this.contenidoVisible ? this.buttonTextVisible : 'Ver contenido';
    }
  },
  mounted() {
    
    this.verContenido();
  }
};
</script>
<style>

</style>