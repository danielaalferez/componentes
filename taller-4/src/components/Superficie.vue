<template>
    <div class="container">
      <nav class="navbar navbar-expand-lg bg-white">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">
            <img src="@/assets/fcf.png" alt="" />
          </a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarScroll"
            aria-controls="navbarScroll"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarScroll">
            <ul class="navbar-nav me-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="https://www.paralympic.org/es/ipc/federations">FEDERACIONES</a>
              </li>
             
              <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <a class="nav-link active" aria-current="page" href="https://fcf.com.co/liga-futsal/tabla-de-posiciones-liga-futsal/">TABLA DE POSICIONES FCF</a>
        <a class="nav-link" href="https://www.conmebol.com/conmebol-copa-america-futsal-femenina/">PARTICIPANTES CONMEBOL</a>
        
      </div>
    </div>
              <li class="nav-item">
                <a class="nav-link" href="https://www.fifa.com/es/tournaments/mens/futsalworldcup">CRONOGRAMA FIFA</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
  
     
      <router-view></router-view>
    </div>
  </template>
  
  <script lang="ts">
  import 'bootstrap/dist/css/bootstrap.css';
  import { defineComponent } from 'vue';
  
  export default defineComponent({
    name: "Superficie",
  });
  </script>
  
  <style>
  .superficie {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: solid 2px white;
    background-color: white;
  }
  
  .navbar-nav .nav-link .nav-link active {
    color: #0400ff;
  }
  </style>
  