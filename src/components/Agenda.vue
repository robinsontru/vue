<template>
<h1>hola soy el componente </h1>
<main>    
  <nav class="menu">
  <li>inicio</li>
  <li>quines somos </li>
  <li>conocete y cuidate </li>
  <li>juegos</li>
  <li>mitos</li>
  <li>verdades</li>
  <li>tutorial</li>
  <li>agenda tu cita</li>
</nav>
<section class="respuesta">
<h1>cancelacion de cita </h1>
<h1>captacionde cita</h1>
</section>

</main>
</template>
<script>

export default {
  
  name: 'Agenda-',
  props: {
    msg: String
  }
} 

</script>
<style>
.menu{
 border: solid 1px;
  list-style: none;
  display: flex;
  justify-content:space-between;
}
.respuesta{
  display: flex;
  justify-content:space-around
}
</style>
