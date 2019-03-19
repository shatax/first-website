<template>
  <v-toolbar color="primary lighten-1">
    <v-toolbar-title>
      <v-btn to="/" flat> Logo
      </v-btn>     
    </v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn to="/about" flat>About</v-btn>
      <v-btn to="/contact" flat>Contact</v-btn>
    </v-toolbar-items>
  </v-toolbar>
</template>

<style>
    .image{
        width: 50px;        
    }
</style>
