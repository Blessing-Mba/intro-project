<template>
      <nav>
        <ul>
      <li class="logo">
      </li>
      <li><router-link to="/features">Features</router-link></li>
      <li><router-link to="/contact">Company</router-link></li>
      <li><router-link to="/contact">Careers</router-link></li>
      <li><router-link to="/contact">About</router-link></li>
      <li><router-link to="/contact">Login</router-link></li>
    </ul>
    <ul class="right-ul">
      <li><router-link to="/login">Login</router-link></li>
      <li>
        <button class="reg-btn">Register</button>
      </li>
    </ul>
      </nav>
    
  </template>
  
  <script>
  export default {
    name: 'NavBar'
  }
  
  
  </script>
  
  <style scoped>
  nav {
    padding: 2rem;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    
  }
  ul{
    width: 40%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    font-size: 14px;
  }
  .right-ul{
    width: 15%;
  }
  .logo{
    background: url(../assets/logo.svg);
    background-size: contain;
    background-repeat: no-repeat;
    height: 3rem;
    width: 7rem;
  }
  .reg-btn{
    width: 6rem;
    height:  1.5rem;
    border: 1px solid black;
    border-radius: 5px;
  }
  </style>
  