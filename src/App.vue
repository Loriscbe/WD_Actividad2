<template>
 <div id="app">
   <h1>ÉCLAT</h1>
    <div id="nav">
      <font size="5">
      <router-link to="/">HOME</router-link> |
      <router-link to="/portfolio">PORTFOLIO</router-link> |
       <router-link to="/video">AL DETALLE</router-link>
      </font><br>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: consolas, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #6e5034;
}

#nav {
  padding: 50px;
}

#nav a {
  font-weight: bold;
  color: #634b37;
}

#nav a.router-link-exact-active {
  color: #291802;
}
body{
  background-color: rgb(235, 225, 212);
  }
</style>
