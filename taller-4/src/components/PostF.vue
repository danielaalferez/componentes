<template>
  <div>
    <button @click="verContenido">{{ buttonText }}</button>
    <div v-if="contenidoVisible">
      {{ contenidoTexto }}
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      buttonText: 'Mostrar :)',
      contenidoVisible: false,
      contenidoTexto: 
      'La fuerza del equipo está en cada miembro individual. La fuerza de cada miembro está en el equipo.'
      
    };
  },
  methods: {
    verContenido() {
     
      this.contenidoVisible = !this.contenidoVisible;
    }
  }
};
</script>
