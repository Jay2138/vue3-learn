<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(1)
</script>

<template>
  <div class="main-container">111</div>
</template>

<style scoped>
.main-container{
  width: 800px;
  height: 800px;
  background-color: pink;
}
</style>
