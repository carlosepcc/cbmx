<template lang="pug">
div.p-5.border-2.border-black.rounded.bg-white.items-center.flex.flex-col                                                                                                                                                                                                                                                                                                                             
    img(v-if="data.icon" :alt="`${data.title} icon`" :src="data.icon??'no'")
    span.text-6xl.font-bold.text-teal-500.font-serif(v-else) {{ data.title[0] }}
    p {{ data.title??'No title' }}
</template>
<script setup lang="ts">
export type Box = {
  icon: string;
  title: string;
};
const props = defineProps<{ data: Box }>();
</script>
