<script setup>
    import { ref } from 'vue'

    const vueLogo = ref('/images/Vue_logo.png')
    const title = ref('Welcome to Vue.js')
    const info = ref('Become a coding ninja with the fastest-growing JavaScript framework')
    const button = ref('Awesome!')
</script>

<template>
    <article>
        <img :src="vueLogo">
        <h1>{{ title }}</h1>
        <p>{{ info }}</p>
        <button>{{ button }}</button>
    </article>
</template>

<style>
    article {
        margin: 28px 72px 0;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        align-items: center;
        letter-spacing: 0.02em;
    }

    h1 {
        margin: 0;
        max-height: 77px;
        width: 100%;
        font-weight: 800;
        font-size: 50px;
        text-align: center;
        line-height: 95px;
        color: #2B2F30;
    }

    p {
        margin: 10px 0 0;
        max-width: 309px;
        text-align: center;
    }

    button {
        margin-top: 22px;
        height: 31px;
        width: 121px;
        color: white;
        background-color: #34495E;
        border: none;
        border-radius: 13px;
    }

    p,
    button {
        font-size: 14px;
        line-height: 20px;
        font-weight: 800;
    }
</style>