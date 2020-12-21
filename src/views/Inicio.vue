<template>
  <div class="home">
    <img class='banner' src=https://secureservercdn.net/198.71.233.41/35g.43f.myftpupload.com/wp-content/uploads/2015/10/cropped-AllCallsBanner.png alt="">
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Inicio',
  components: {
    HelloWorld
  }
}
</script>
<style scoped>
  .banner{
    width: 100%;
    height: auto;
  }
</style>