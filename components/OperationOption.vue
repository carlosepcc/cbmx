<template>
  <div class="flex">
    <span class="text-grey-500">{{ props.text ?? "" }}</span>
    <span v-html="props.svg"></span>
    <img :src="props.iconUrl" />
  </div>
</template>
<script setup lang="ts">
const props = defineProps<{ text: string; svg?: string; iconUrl?: string }>();
</script>
