<template lang="pug">
div.box.border-2.border-black.rounded-xl.bg-white.flex.flex-col.items-center.justify-center                                                                                                                                                                                                                                                                                                                          
    img(v-if="data.icon" :alt="`${data.title} icon`" :src="data.icon??'no'")
    div(v-if="data.svg" v-html="data.svg")
    span.text-6xl.font-bold.text-teal-500.font-serif(v-else) {{ data.title[0] }}
    p {{ data.title??'' }}
</template>
<script setup lang="ts">
export type Box = {
  icon?: string;
  svg?: string;
  title: string;
};
const props = defineProps<{ data: Box }>();
</script>
<style lang="sass">
.box
  aspect-ratio: 1
  width: 132px
svg
:
  width: 50px
</style>
