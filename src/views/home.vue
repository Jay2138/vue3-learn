<script setup>
import ModelButton from '../components/ModelButton.vue'
import { ref } from 'vue'


const name = ref('Tom')
const changeName = () => {
  name.value = 'Marry'
}
</script>
<template>
  <div class="main-container">
    <h2>姓名: {{  name  }}</h2>
    <button @click="changeName">改变姓名</button>
    <!-- teleport: ModelButton -->
    <ModelButton></ModelButton>
  </div>
</template>
<style>
.main-container {
  /* margin: 0 auto; */
}
</style>