<template>
  <div class="about">
    <h1>This is an about page</h1>
    <HelloWorld></HelloWorld> 
  </div>
</template>

<script>
  import HelloWorld from '@/components/HelloWorld.vue'
  export default{
  name: 'AboutVue',
  components: {
    HelloWorld
  }
  }
</script>