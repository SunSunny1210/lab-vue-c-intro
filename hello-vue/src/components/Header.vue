<script setup>
import { ref } from 'vue'

const ihLogoSrc = ref('/images/Ironhack_logo.png')
const burgerMenu = ref('/images/Burger_menu.png')
</script>

<template>
    <header>
        <img class="logo" :src="ihLogoSrc">
        <img class="burger" :src="burgerMenu">
    </header>
</template>

<style scoped>
    header {
        margin: 20px 30px 0;
        max-width: 540px;
        width: 100%;
        background-color: white;
        display: flex;
        justify-content: space-between;
        align-items: center;

    }

    .logo {
        height: 38px;
        width: 35px;
    }
</style>