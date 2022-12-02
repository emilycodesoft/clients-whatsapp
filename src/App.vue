<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Navbar</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarColor01"
        aria-controls="navbarColor01"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarColor01">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#"
              >Numeros Clientes</a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Productos</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Fechas de apertura</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Mensaje</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Envio</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <Mensaje></Mensaje>
  <!-- <FechasApertura></FechasApertura> -->
  <!-- <Productos></Productos> -->
  <!-- <NumerosCliente></NumerosCliente> -->
</template>

<script>
import NumerosCliente from "@/views/NumerosCliente";
import Productos from "@/views/Productos";
import FechasApertura from "@/views/FechasApertura";
import Mensaje from "@/views/Mensaje";
export default {
  name: "App",
  components: { NumerosCliente, Productos, FechasApertura, Mensaje },
};
</script>

<style>
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */
}
</style>
