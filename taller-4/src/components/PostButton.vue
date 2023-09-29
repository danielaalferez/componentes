<template>
    <button class="post-button">Ver Contenido</button>
</template>

<script lang="ts">
    import { defineComponent, DefineComponent } from 'vue';

    export default defineComponent({
        name: "PostButton"
    })
</script>

<style lang="scss" scoped>
.post-button {
    background-color: rgb(237, 104, 237);
    padding: 3px;
    border: solid 1px rgb(52, 8, 148);
    &:hover{
        background-color: rgb(107, 7, 114);
        border: solid px rgb(3, 30, 80);
        color: #ffffff;
    }
}
</style>