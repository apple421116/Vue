<script setup>
import Demo from './components/Demo.vue'
</script>

<template>
    <div>
        <Demo msg="Please select one website to visit"></Demo>
        
        <a href="https://www.google.com" target="_blank">
        <img src="./assets/google-logo-9808.png" class="logo" alt="Google" />
        </a>
        <a href="https://www.youtube.com" target="_blank">
        <img src="./assets/youtube-logo-png-2067.png" class="logo youtube" alt="Youtube" />
        </a>
        <a href="https://www.avgle.com" target="_blank">
        <img src="./assets/avgle logo.png" class="logo avgle" alt="avgle" />
        </a>
        <a href="https://www.pornhub.com" target="_blank">
        <img src="./assets/PH logo.png" class="logo pornhub" alt="Pornhub" />
        </a>
    </div>
</template>

<style scoped>
    .logo {
        height: 6em;
        padding: 1.5em;
        will-change: filter;
        transition: filter 300ms;
    }

    .logo:hover {
        filter: drop-shadow(0 0 1.5em #648dffaa)
    }

    .logo.youtube:hover {
        filter: drop-shadow(0 0 1.5em #ca4545aa);
    }
    .logo.avlge:hover {
        filter: drop-shadow(0 0 1.5em #648dffaa);
    }
    .logo.pornhub:hover {
        filter: drop-shadow(0 0 1.5em #f8b437aa);
    }
</style>