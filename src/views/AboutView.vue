<script lang="ts" setup>
const msg =  '这是一个标题；'
</script>
<template>
  <div class="about">
    <h1>This is an about page</h1>
    <br>
    <h2>{{ msg }}</h2>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
