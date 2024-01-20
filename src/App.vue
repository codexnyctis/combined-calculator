<script setup>
import ElectricCar from './components/ElectricCar.vue'
import FuelCar from './components/FuelCar.vue';
</script>

<template>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Handjet:wght@300&family=Montserrat:ital,wght@0,200;0,600;1,300;1,900&display=swap" rel="stylesheet">
  <div class="title neon-text">
    <h1>FUEL - ELECTRIC CAR</h1>
    <h2>Energy Cost Calculator</h2>
  </div>
  <div class="mainApp">
    <ElectricCar />
    <FuelCar />
  </div>        
</template>

<style>
.mainApp {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  gap: 4em;
  height: 100vh;
  padding-top: 2em;
  margin-bottom: 3em;
}

.title h1, .title h2 {
  margin: 0; 
}

.title h1 {
  font-size: 2em;
}

.title {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: #fff; /* Set text color to white */
  margin: 2em auto 3em auto;
  
  font-family: Montserrat;
}

.neon-text h1 {
  text-shadow: 0 0 10px #4b4d57, 0 0 10px #56596a, 0 0 10px rgb(88, 60, 122), 0 0 20px rgb(45, 2, 85), 0 0 50px rgb(35, 5, 83), 0 0 60px rgb(32, 1, 50);
}
</style>
