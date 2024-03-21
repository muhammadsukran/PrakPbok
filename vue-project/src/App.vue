<template>
  <div>
   <h1> Hello World</h1>
    <Buttonc />
    <Buttonc />

  </div>
  </template>


  <style scoped>
  .btn {
    background-color: red;
    color: white;
    font-size: 28px;
  }
</style>

<!-- vue 3 -->
<script setup>
  import Buttonc from './components/Buttonc.vue'
</script>