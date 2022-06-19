<template>
  <div class="about">
    <h1>This is an about page</h1>
    <MidBackground></MidBackground> 
  </div>
</template>

<script>
  import MidBackground from '@/components/MidBackground.vue'
  export default{
  name: 'AboutVue',
  components: {
    MidBackground
  }
  }
</script>