<template>
  <div>
      <header>
         <h1>Viú para dummmies</h1>
      </header>
  </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style>

header {
  height: 5rem; /* Full-height: remove this if you want "auto" height */
  width: 100%; /* Set the width of the sidebar */
  position: fixed; /* Fixed Sidebar (stay in place on scroll) */
  z-index: 1; /* Stay on top */
  top: 0; /* Stay at the top */
  left: 0;
  background-color: #111; /* Black */
  display: flex;
  justify-content: center;
  align-items: center;
}

h1{
  text-align: center;
  font-size: 3rem;
  color: aliceblue;

}
</style>