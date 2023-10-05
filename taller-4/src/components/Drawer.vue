<template>
     <div class="Drawer">
      
    <plate v-for="post in posts" :key="post.title"
       :title="post.title"
       :summary="post.summary"
       :imagen="post.imagen"
       :text="post.text" 
       :link="post.link"
    />
    
</div>

  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  import Plate from './Plate.vue';
  import datos from '@/assets/posts.json'
  
  export default defineComponent({
    name: "Drawer",
    components: {
      Plate
    },
    data() {
      return {
        posts: datos
      }
    }
  })
  </script>
  
  <style lang="scss" scoped>
  .Drawer {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    background-color:rgb(204, 217, 241);
    border: solid 2px rgb(170, 210, 253);
  }
imagen{
    width: 200px;
}

  </style>
  