<template>
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
    <section> 
    <h1 class="cita">correo institucional</h1>
    <div class="cita">
      <input type="emaill">
      <input type="button" value="agendar">
 
    </div>
    <h2>El agendamiento de la cita te llegara al correo misena </h2>
    <h1 class="caledario">Agenda tu cita</h1>
  </section>
  </main>
</template>
<script>
export default {
  
  name: 'Cita-',
  props: {
    msg: String
  }
}
</script>
<style  >
.menu {
  list-style: none;
  display: flex;
  justify-content: space-around;
  border: solid 1px;
}

.cita {
  display: flex;
  justify-content:flex-start
}

.caledario {
  display: flex;
  justify-content: end
}
h2{
  display: flex;
  justify-content:flex-start
}
</style>