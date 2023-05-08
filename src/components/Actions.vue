<script setup>
  import { ref } from "vue";
  const count = ref(0);
</script>
<template>
   <div class="actions">
    <!-- Font Awesome icons -->
    <i class="far fa-comment"></i>
    <i class="fas fa-retweet"></i>
    <i class="far fa-heart" @click="count++">
      <span class="plus-sign">+</span>
      <span class="counter">{{ count }}</span>
    </i>
    
    <i class="fas fa-share"></i>
  </div>
</template>


