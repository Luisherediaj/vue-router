<template>
  <ul>
    <li>Rutas</li>
    <li>Frameworks</li>
    <li>Documentación</li>
    <li>Vuex</li>
    <li>Otras movidas</li>
  </ul>
</template>

<script>
export default {
    Name: 'Browser'
}
</script>

<style>
ul {
    list-style-type: none;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}

li {
    float: left;
}

li {
    display: block;
    color: white;
    text-align: center;
    padding: 16px;
    text-decoration: none;
    border-right: 1px solid #bbb;
}


li:hover {
    background-color: #111;
}
</style>