<template lang="pug">
div
    AppHeader
    v-main.px-4
            slot No content
    footer 
        p
            span tranquilo 
            AppLogo
            span se encarga
</template>

<script setup lang="ts">
import { useRoute } from "vue-router";
const route = useRoute();
</script>
