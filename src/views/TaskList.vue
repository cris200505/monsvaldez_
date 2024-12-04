<template>
    <div class="container mt-4">
        <h1><span style="color: orange">Me regalas una foto?</span></h1>
        <div class="container mt-5">
            <p class="lead text-secondary mb-4">
                    Desde aquel 17 de agosto, como te dije en varias oportunidades, me dejaste impresionado, 
                nunca antes había visto una chica tan linda e inteligente, conocerte ahí para mí fué algo genial,
                por eso desde un principio lo único que quería era una forma de contactarte después de la competencia,
                gracias a que me hablaste y después tuve el valor de pedirte la foto es que cumplí ese propósito  y hoy 
                te convertiste en una persona sumamente importante para mí.
            </p>
            <img src="@/assets/compe.png" class="img-fluid mb-4 logo" alt="Vue logo" />
            <img src="@/assets/compe3.png" class="img-fluid mb-4 logo" alt="Vue logo" />
            <img src="@/assets/compe5.png" class="imagen" alt="Vue logo" />
            <img src="@/assets/compe6.png" class="imagenx" alt="Vue logo" />

            <ul class="navbar-nav ms-auto">         
            <li class="boton">
              <router-link class="boton1" to="/addtask">
                <i></i>‹‹ Anterior
              </router-link>
              <router-link class="boton2" to="/combined">
                <i></i>Siguiente ››
              </router-link>
            </li>
          </ul>
        </div>
    </div>
</template>

<style scoped>
.container .imagenx{
    padding: 4px;
  border-radius: 40px;
  box-shadow: 0 0 5px rgba(200, 243, 81, 0.5);
  transition: transform 0.3s, box-shadow 0.3s;
  width: 300px; 
  height: 200px;
}
.container {
    max-width: 800px;
    padding: 20px;
    text-align: center;
}

h1 {
    font-size: 50px;
    font-weight: bold;
    font-family: 'Times New Roman', Times, serif;
    text-shadow: 2px 2px 3px rgba(0, 0, 0, 3);
    text-align: center;
}

.task-input {
    border-radius: 25px;
    transition: border-color 0.2s;
}

.task-input:focus {
    outline: none;
    box-shadow: 0 0 5px rgba(63, 218, 42, 0.5)
}

.card-title {
    font-weight: bold;
    overflow-wrap: break-word;
    max-height: 3em;
    overflow: hidden;
}

.text-decoration-line-through {
    text-decoration: line-through;
}

.logo {
  padding: 4px;
  border-radius: 40px;
  box-shadow: 0 0 5px rgba(200, 243, 81, 0.5);
  transition: transform 0.3s, box-shadow 0.3s;
  width: 300px; 
  height: 400px;
}

.imagen {
    padding: 4px;
  border-radius: 40px;
  box-shadow: 0 0 5px rgba(200, 243, 81, 0.5);
  transition: transform 0.3s, box-shadow 0.3s;
  width: 300px; 
  height: 200px;
}

.boton-container {
  text-align: center;
    gap: 10px; 
}

.boton {    
  display: inline-block ;
  margin: 5px;
  padding: 10px 20px;
  color: white;
  border:rgb(2, 0, 0);
  border-radius: 5px;
  cursor: pointer;
}
.boton1{
    margin: 30px;
}

.boton2{
    margin: 30px;
}
</style>