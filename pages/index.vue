<template lang="pug">
div
    div#top-boxes.mx-16.mb-20.flex.flex-wrap.gap-8.justify-center
        template(v-for="box in boxes" v-bind:key="box.title")
            BoxCard.w-40(:data="box")
    WelcomeMessage
    PromoMessage
</template>
<script setup>
import { ref } from "vue";
const boxes = ref([
  {
    title: "Remesas",
  },
  {
    title: "Tienda",
  },
  {
    title: "Recargas",
  },
  {
    title: "Viajes",
  },
  {
    title: "Consulado",
  },
  {
    title: "Paquete",
  },
  {
    title: "Hotel",
  },
  {
    title: "Auto",
  },
]);
</script>
