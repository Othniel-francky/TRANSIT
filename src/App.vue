<template>
  <Navbar />
  <router-view/>
</template>

<script>
  import Navbar from '@/components/Navbar.vue'
export default {
  name: 'App',
  components:{
    Navbar

}
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
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
