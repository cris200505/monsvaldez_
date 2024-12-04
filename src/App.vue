<template>
  <div id="app">
    <nav style="background-color: #85db34;" class="navbar navbar-expand-lg navbar-dark bg-primary shadow-sm">
      <div class="container">
        <!-- Título de la aplicación -->
        <router-link class="navbar-brand d-flex align-items-center" to="/">
          <img src="@/assets/bailarina.png" alt="Vue logo" width="30" height="30" class="d-inline-block align-top me-2" />
          <p><span style="font-family: 'Times New Roman', Times, serif;">¡¡Feliz Cumpleaños!!</span></p>
        </router-link>

        <!-- Botón de toggler para pantallas pequeñas -->
        <button
          class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <!-- Contenido del navbar -->
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">         
            <li class="nav-item">
              <router-link class="nav-link d-flex align-items-center" to="/addtask">
                <img src="@/assets/cerro.png" alt="Vue logo" width="30" height="30" class="d-inline-block align-top me-2" />
                <i></i>15 //
              </router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link d-flex align-items-center" to="/tasklist">
                <img src="@/assets/roque.png" alt="Vue logo" width="40" height="30" class="d-inline-block align-top me-2" />
                <i></i>12 //
              </router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link d-flex align-items-center" to="/combined">
                <img src="@/assets/depor.png" alt="Vue logo" width="34" height="30" class="d-inline-block align-top me-2" />
                <i></i>2024
              </router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link d-flex align-items-center" to="/about">
                <i></i>👁👁No ver
              </router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <router-view />
  </div>
</template>

<style>
.container {
  color:blueviolet;
}

.nav{
  background-color: #85db34; /* Cambia el color del fondo */
  color: white;
  color:blueviolet;
}