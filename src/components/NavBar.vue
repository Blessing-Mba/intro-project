<template>
      <nav>
        <ul>
      <li class="logo">
      </li>
      <li><router-link to="/about">Features</router-link></li>
      <li><router-link to="/contact">Company</router-link></li>
      <li><router-link to="/contact">Careers</router-link></li>
      <li><router-link to="/contact">About</router-link></li>
      <li><router-link to="/contact">Login</router-link></li>
    </ul>
      </nav>
    
  </template>
  
  <script>
  export default {
    name: 'NavBar',
    
  }
  
  
  </script>
  
  <style scoped>
  nav {
    padding: 2rem;
    
  }
  ul{
    width: 40%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }
  .logo{
    background: url(../assets/logo.svg);
    background-size: contain;
    background-repeat: no-repeat;
    height: 3rem;
    width: 7rem;
  }
  </style>
  