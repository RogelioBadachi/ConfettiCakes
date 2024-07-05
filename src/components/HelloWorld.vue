<template>
  <div class="hello">
    <h2>{{ text }}</h2>
    <h1> <pre>{{ msg }}</pre></h1>
    <div class="aboutContainer">
      <p>Our company started in 2016</p>
      <p>We make the most delicious cakes in town</p>
    </div>
    <!-- <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p> -->
    
  </div>

</template>

<script>


export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data(){
    return {
      text: "Welcome to Confetti Cakes!", 
      msg: "Hello World"
    }
  }
}
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
pre {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 
  Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
/* Suggested code may be subject to a license. Learn more: ~LicenseLog:3384507161. */
.aboutContainer {
  background-image: linear-gradient(45deg, rgba(255, 166, 0, 1) 14.7%, rgba(255, 99, 97, 1) 73%);  
  }
</style>
