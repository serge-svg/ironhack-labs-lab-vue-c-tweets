<script setup>
  const props = defineProps({
    name: String,
    handle: String,
  });

</script>

<template>
    <span class="name">{{ name }}</span>
    <span class="handle">{{ handle }}</span>
</template>
