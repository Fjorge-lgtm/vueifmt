<template>
    <div class="hello">
      <h1>{{ msg }}</h1>
      <p>
        Neste local devemos ter "tags" de formulário,<br>
        algum trabalho foi necessario para chegar até aqui.
      
      </p>
      
    </div>
</template>
  
  <script>
  export default {
    name: 'FormularioGeral',
    props: {
      msg: String,
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  h3 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #a142b9;
  }
  </style>
  