
<script>
import HomeLink from './components/HomeLink.vue'
import NavLink from './components/NavLink.vue'

export default {
  name: 'App',
  components: {
    HomeLink,
    NavLink
  }
}
</script>

<template>
  <div id="app">
      <HomeLink />
    <nav>
      <NavLink url="/" text="Home" />
      <NavLink url="/about" text="About" />
      <NavLink contact="/" text="Contact" />
      
    </nav>
    <p>Welcome to our <HomeLink /> page!</p>
  </div>
</template>
 
<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
