<script setup>
  const props = defineProps({
    image: String
  });

</script>

<template>
    <img
      :src="image"
      class="profile"
      alt="profile"
    />
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
