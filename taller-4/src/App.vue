<template>
  
 
  <br>
  <div class="background-drawer">
    <Superficie/>
    
    <h1>LIGAS DE FUTSALA FEMENINO</h1>
  
  <h2><em>El fútbol sala femenino es una versión rápida y emocionante del fútbol tradicional, que promueve el juego en equipo y las habilidades técnicas. Su historia y reglas únicas lo convierten en una disciplina deportiva apasionante tanto para jugadoras como para espectadores,
   ya que es un deporte apasionante que ha experimentado un crecimiento significativo en los últimos años. Las jugadoras de fútbol sala femenino muestran una destreza excepcional en la cancha, combinando habilidad, velocidad y agilidad. Este deporte no solo es emocionante de ver, sino que también inspira a muchas mujeres y niñas a seguir sus pasiones deportivas.
  </em></h2>
  <br>
  </div>
  
  
  <br>
 
  <drawer/>
  

</template>

<script lang="ts">
import { defineComponent, DefineComponent } from 'vue';
import Drawer from './components/Drawer.vue';
import Superficie from './components/Superficie.vue';
import PostF from'./components/PostF.vue';
export default defineComponent({
  components: {
    Drawer,
    PostF,
    Superficie
  }
})

</script>

<style lang="scss">

h1{
  color: rgb(102, 13, 103);
  text-align: center;
}
.image-drawer {
 
 justify-content: center;
 
}
p{
  text-align: left;
  color:navy ;
  text-decoration:double;
 font-size: 20px;
}
Button{
  color:darkblue;
  float: left;
  font-size: 20px;
}
h3{
  color: rgb(102, 11, 148);
  font-size: 25px;
}

div{
  background-color:#aec6f4;
  border: 3PX slateblue;
  
}
.post.imagen{
 max-width: 250 px;
  max-height: 300px;
}
h2{
  color: darkslateblue;
  font-size: larger;
  font-family:Arial, Helvetica, sans-serif;
  text-align: justify;
}
.image-drawer{
  width:350;
  height:200;
}
.background-drawer{
 
  background-color: aliceblue;
  width: 100%;
   
    flex-wrap: wrap;
    background-color:rgb(204, 217, 241);
  
  
  
   

}


</style>
