<template>
      <Header/>
      <Main/>
      <Footer/>
     <div id="app">
        <div id="nav">
            <router-link to="/">Home</router-link> 
            <router-link to="/about">About</router-link>
            <router-link to="/contacto">Contacto</router-link>
        </div>
        <router-view/>
    </div>
</template>

<script>

import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Main
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
#nav {

  width: 15rem; /* Set the width of the sidebar */
  position: fixed; /* Fixed Sidebar (stay in place on scroll) */

  top: 6rem; /* Stay at the top */
  left: 0;
  background-color: #111; /* Black */
  overflow-x: hidden; /* Disable horizontal scroll */

}

/* The navigation menu links */
#nav router-link {
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-size: 20px;
  color: aliceblue;
  display: block;
}

/* When you mouse over the navigation links, change their color */
#nav router-link:hover {
  color: #818181;
}
</style>
