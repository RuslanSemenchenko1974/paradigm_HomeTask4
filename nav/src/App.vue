<template>
  <nav>
    <router-link to="/">Task Home 4 describe</router-link> |
    <router-link to="/TaskHome4"> Task Home 4 decision</router-link> |
  </nav>
  <router-view/>
</template>
<script>
import TaskHome4 from "@/pages/TaskHome4.vue"
export default{
  components:{
    
  }
}
</script>
<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;
    margin: 10px;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
