<template>
  <div class="card" style="width: 18rem">
    <slot name="pic"></slot>

    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">
        Some quick example text to build on the card title and make up the bulk
        of the card's content.
      </p>
      <likesad></likesad>
    </div>
  </div>
</template>
<script setup>
import likesad from "./like-sad.vue";
</script>
