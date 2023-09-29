<template>
    <div class="post-card">
        <h3>{{ title }}</h3>
        <p>
            {{ summary }}
        </p>
        <p>
            {{ text }}
        </p>
        <post-button/><br>
        <br>
        <post-F/>
    </div>
</template>

<script lang="ts">
import { defineComponent, DefineComponent } from 'vue';
import PostButton from './PostButton.vue';
import PostF from './PostF.vue';

export default defineComponent({
    name: "PostCard",
    components: {
        PostButton,
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
        text : {
            type: String,
            default: ""
        }
    }
})
</script>

<style lang="scss" scoped>
.post-card {
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: solid 1px #e061f0;
}
</style>