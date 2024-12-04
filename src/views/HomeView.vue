<template>
  <div class="container mt-5">
    <div class="text-center">
      <h1 ><span style="color: blue">Claudia</span><span style="color: red"> Monserrat</span> 
        <span style="color: green"> Valdez</span> <span style="color: red">Torres</span></h1>
      <p class="lead text-secondary mb-4">
        ¡¡FELIZ CUMPLEAÑOS A LA CHICA MÁS GENIAL DE ESTE MUNDO!!
      </p>
      <img src="@/assets/imagen34.png" class="img-fluid mb-4 logo" alt="Vue logo" />
      <p class="lead text-secondary mb-4">
          ~Pd: Espero y me disculpes por el contenido de la página jajajaja. Feliz 20 años 
        pesadita, dándole clic a cualquiera de los escudos (Tu querido Cerro Porteño (ndovalei kaka)
        , la gloriosa Selección Roquegonzaleña (nuestra compañía más grande) o el gran Deportivo 
        Roque Gonzalez (pea si ñande club)) vas a poder vizualizar este pequeño detalle que te hice.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeView',
};
</script>

<style scoped>
.container {
  max-width: 900px;
}

.display-4 {
  border-radius: 50px;
  font-weight: bold;
  text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2);
}
.logo {
  padding: 12px;
  border-radius: 40px;
  box-shadow: 0 0 10px rgba(70, 14, 199, 0.5);
  transition: transform 0.3s, box-shadow 0.3s;
  width: 300px; 
  height: 400px;
}

.logo:hover {
  transform: scale(1.1);
  box-shadow: 0 0 10px rgba(252, 12, 12, 0.7)
}

h2 {
  font-weight: bold;
}

.text-muted {
  font-size: 1rem;
}
.lead {
  font-size: 1.25rem;
}
h1 {
  font-family: 'Times New Roman', Times, serif;
  font-size: 60px;
}

p {
  font-family:'Times New Roman', Times, serif;
}
</style>
