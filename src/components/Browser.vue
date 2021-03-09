<template>
<div class="sidenav">
    <a href="#">Rutas</a>
    <a href="#">Frameworks</a>
    <a href="#">Documentación</a>
   <a href="#">Vuex</a>
    <a href="#">Otras movidas</a>

  </div>
</template>

<script>
export default {
    Name: 'Browser'
}
</script>

<style>
.sidenav {

  width: 15rem; /* Set the width of the sidebar */
  position: fixed; /* Fixed Sidebar (stay in place on scroll) */

  top: 6rem; /* Stay at the top */
  left: 0;
  background-color: #111; /* Black */
  overflow-x: hidden; /* Disable horizontal scroll */

}

/* The navigation menu links */
.sidenav a {
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-size: 20px;
  color: aliceblue;
  display: block;
}

/* When you mouse over the navigation links, change their color */
.sidenav a:hover {
  color: #818181;
}
</style>