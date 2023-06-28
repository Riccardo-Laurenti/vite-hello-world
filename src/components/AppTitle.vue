<template>
  <h1 class="title">{{titolo}}</h1>
</template>

<script>
  export default {
      data() {
          return{
              titolo: 'La mia prima app con Vite!'
          }
      }
  }
</script>

<style>
  .title{
      color: rgb(80, 81, 167);
  }
</style>