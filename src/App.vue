<template>
  <nav>
    <router-link to="/">Accueil</router-link> |
    <router-link to="/about">A propos</router-link> |
    <router-link to="/portfolio">Portfolio</router-link>
  </nav>
  <router-view/>
</template>

<style lang="scss">
html {
  background-color: #0f203a;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color:aliceblue;
  background-color: #0f203a;
}

h1{
  width: 70%;
  color:#fde169;
  display: flex;
  justify-content: flex-start;
  border-bottom: 4px solid #fde169;
  padding-bottom: 3%;
}

p{
  margin: 0;
  color: white;
  display: flex;
  justify-content: flex-start;
    
}

nav {
  padding: 7%;
  
  a {
    font-weight: bold;
    color: white;
    text-decoration: none;

    &.router-link-exact-active {
      color: #fde169;
    }
  }
}
</style>
