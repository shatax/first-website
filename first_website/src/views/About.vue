<template>
    <v-container>
      <div>
      <img class="hero-image" src="../assets/shatax.jpg" alt="logo image" style="width:100%">
      </div>
      <div class="hero-text">
        <h2>Practice Template Website</h2>
  <h1 style="font-size:50px">I am Noor.</h1>
  <p> I created this site as a practice template</p>
      </div>
    </v-container>
</template>

<style>
.hero-image {
  height: 50%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
  filter: blur(3px);
  -webkit-filter: blur(3px);
  height: 100%; 
  
  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.hero-text {
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0, 0.4); /* Black w/opacity/see-through */
  color: white;
  font-weight: bold;
  border: 3px solid #f1f1f1;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 2;
  width: 80%;
  padding: 20px;
  text-align: center;
}
</style>