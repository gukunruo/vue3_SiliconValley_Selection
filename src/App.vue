<template>
  <div class="box">
    <h1>App根组件</h1>
  </div>
</template>

<script setup lang="ts">
const str = 'xxx'
for (let i = 0; i < str.length; i++) {
  console.log('a')
}
</script>

<style scoped lang="scss">
.box {
  width: 600px;
  height: 400px;
  background: black;
  h1 {
    color: white;
  }
}
</style>
