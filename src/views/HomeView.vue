<template>
  <div class="home">

    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome! Here you'll be able to customize your own homemade 
    flavored cake. These cakes are the best in town!"/>
    <MidBackground></MidBackground> 
    <!--<MidBackgroundVueCopy></MidBackgroundVueCopy>-->
    <FooterVue></FooterVue>




    
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import FooterVue from '@/components/Footer.vue' 
//import MidBackgroundVue from '@/components/MidBackground.vue'
import MidBackground from '../components/MidBackground.vue'
import MidBackgroundVueCopy from '@/components/MidBackground copy.vue'


export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    FooterVue,
    MidBackground,
    MidBackgroundVueCopy
    
}
}
</script>
<style scoped>
  div{
    padding-top: 3rem;
  }
  img{
    height: 300px;
    width: 300px;
  }
</style>
