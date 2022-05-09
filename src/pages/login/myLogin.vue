<template>
  <div class="login">
    <h1>Vite2 + Vue3 + TypeScript + Pinia 开发脚手架</h1>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<style lang="scss" scoped>
.login {
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
h1 {
  text-align: center;
  color: $test-color;
}
</style>
