<template>
  <h1>LIGAS DE FUTBOL</h1>
  <div class="image-container">
  <img alt="Vue logo" src="./assets/futbol.png" width="400" height="200" >
  <img alt="Vue logo" src="./assets/futsal.jpg" width="300" height="200">
  <img alt="Vue logo" src="./assets/fut.jpg" width="300" height="200">
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
