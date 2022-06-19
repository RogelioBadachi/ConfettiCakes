<template>
  <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> | 
      <router-link to="/shop">Shop</router-link> | 
    <div class="shoppingCart"><router-link to="/cart"><i class="fa-solid fa-cart-shopping"></i></router-link> </div> 
  </nav>
    <h3>Confetti Cakes</h3>
  <router-view/>

</template>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}
nav div{
  position: absolute;
  right: 0;
  top: 0;
  font-size: 2.5rem;
}

h3{
  padding-top: 1.8rem;
font-family: "Brush Script MT", cursive; font-size: 35px; 
font-style: normal; font-variant: normal; font-weight: 700; line-height: 26.4px;
color: rgb(48, 21, 145);
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}

</style>
