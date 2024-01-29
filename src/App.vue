<template>
  <h4>123</h4>
</template>

<script setup lang="ts">
import { onMounted } from 'vue'
import { reqLogin } from './api/user'
onMounted(() => {
  reqLogin({ username: 'admin', password: '111111' })
})
</script>

<style scoped lang="scss">
h4 {
 color: $color;
}
</style>
