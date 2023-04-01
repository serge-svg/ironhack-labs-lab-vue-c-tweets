<script setup>
  const props = defineProps({
    timestamp: String
  });

</script>

<template>
    <span class="timestamp">{{ timestamp }}</span>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
