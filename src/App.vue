<template>
  <div id="app">
    <!-- Menggunakan router link untuk memanggil path dari router folder untuk menampilkan page -->
    <NavbarShop />
    <router-view/>
  </div>
</template>

<script>
import NavbarShop from './components/NavbarShop.vue';

export default {
  components: {
    NavbarShop
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  font-family: Arial;
}

#page-wrap {
  margin: auto;
  max-width: 800px;
  min-width: 100vh;
}

button {
  background-color: #418883;
  border: none;
  border-radius: 8px;
  color: white;
  cursor: pointer;
  font-size: 16px;
  font-weight: bold;
  outline: 0;
  padding: 16px;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
