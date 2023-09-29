<template>
  <h1>LIGAS DE FUTBOL</h1>
  <div class="image-container">
  <img alt="Vue logo" src="./assets/futbol.png" width="400" height="200" >
  <img alt="Vue logo" src="./assets/futsal.jpg" width="400" height="200">
  <img alt="Vue logo" src="./assets/fut.jpg" width="350" height="200">
  <br>
  <a href="https://www.flashscore.co/futbol-sala/europa/uefa-futsal-champions-league/#/zg">Resultados Champions</a><br>
  <a href="https://www.conmebol.com/noticias/el-cierre-de-los-grupos-en-la-conmebol-copa-america-futsal-femenina/">Cierre de CONMEBOL</a><br>
  <a href="https://european-union.europa.eu/priorities-and-actions/eu-priorities/achievements_es">Logros de la Union Europea</a>
  
  <post-container/>
</div>
</template>

<script lang="ts">
import { defineComponent, DefineComponent } from 'vue';
import PostContainer from './components/PostContainer.vue';
export default defineComponent({
  components: {
    PostContainer
  }
})
</script>

<style lang="scss">
h1{
  color: rgb(182, 13, 117);
  text-align: center;
}
.image-container {
 
 justify-content: center;
}
p{
  text-align: left;
  color:navy ;
  text-decoration:double;
}
button{
  color:darkblue;
}
h3{
  color: darkorchid;
}

</style>
