<template lang="pug">
div
    header
        nav.bg-white.p-6.flex.row.justify-between
            h1.text-teal-600(title="CUBAMAX") CUBAMAX
            div
                small (310) 324 0330
                div.flex.justify-between
                    v-btn
                        NuxtLink(to="/") I
                    v-btn
                        NuxtLink(to="products") P
                    v-btn
                        NuxtLink(to="about") A
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
