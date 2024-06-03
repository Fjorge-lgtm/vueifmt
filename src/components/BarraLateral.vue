<template>
    <div class="hello">
      <h1>{{ msg }}</h1>
      <p> Nossas experiências com Vue.js são excelentes.</p>
      
    </div>
  </template>
  
  <script>
  export default {
    name: 'BarraLateral',
    props: {
      msg: String
    }
  }
  </script>

  <style scoped>
   
  h3 {
    color:rgb(19, 8, 37);
    }
  </style>
  