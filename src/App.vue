<template>
      <Header/>
      <Browser/>
      <Main/>
      <Footer/>
      <div>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/contact">Contact</router-link>
      <router-view />
      </div>
</template>

<script>

import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Browser from './components/Browser.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Main,
    Browser
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  color: #2c3e50;
  display: grid;
    grid-template-columns: 18rem 60rem;
}

</style>
