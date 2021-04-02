<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo_large.png" height="150px">
    <Home msg="Welcome to Music Application"/>
    <Article msg = "Article Page"/>
    <Tab msg= "Tab page"/>
    <About msg = "About page"/>
  </div>
</template>

<script>
import Home from './components/Home.vue'
import Tab from './components/Tab.vue'
import Article from './components/Article.vue'
import About from './components/About.vue'

export default {
  name: 'App',
  components: {
    Home,
    Tab,
    Article,
    About
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
