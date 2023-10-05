<template>
    <div class="plate">
        <h3>{{ title }}</h3>
        <img :src="require(`@/assets/${imagen}`)" alt="" class="" />
        
        <p>
            {{ summary }}
        </p>
    
        <p>
            {{ text }}
        </p><br>
        <p>
            <a :href="link">Información Futsal</a>
        </p>
        
        <post-F/>
    </div>
</template>

<script lang="ts">
import { defineComponent, DefineComponent } from 'vue';
import PostF from './PostF.vue';

export default defineComponent({
    name: "PostCard",
    components: {
       
        PostF
    },
    
    
    props: {
        title : {
            type: String,
            default: ""
        },
        
        summary : {
            type: String,
            default: ""
        },
        imagen : {
            type: String,
            default: ""
        },

        text : {
            type: String,
            default: ""
        },
        link : {
            type: String,
            default: ""
        }
    }
})
</script>

<style lang="scss" scoped>
.plate {
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: solid 2px #8fb0f0;
    background-color: rgb(249, 249, 249);

}
</style>