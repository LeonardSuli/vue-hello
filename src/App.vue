<script>
  export default {
    data() {
      return {
        message: 'hello',
        image: './assets/vue.svg'
      }
    }
  }
</script>

<template>
  <h1>{{ message }}</h1>
  <img :src='image'  alt="">
</template>

<style>

</style>
