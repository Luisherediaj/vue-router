<template>
      <Header/>
      <Browser/>
      <Main/>
      <Footer/>
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
  /* grid-template-areas:
    'header header header header'
    'browser main main main'
    'browser main main main'
    'footer footer footer footer'; */
    grid-template-columns: 20rem 50rem;
  grid-template-rows: 4rem 2.5rem 6rem 6rem 6rem;
}

</style>
