<script setup>
  const props = defineProps({
    message: String,
  });

</script>

<template>
    <p class="message">
      {{ message }}
    </p>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
