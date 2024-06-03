<template>
    <div class="hello">
      <h1>{{ msg }}</h1>
      <p>
        Ainda nao apredi as rotas,<br>
        razão pela qual estes componentes estarem embolados, <br>
        dessa forma é necessário mais tempo para aprender a fazer.
        
      </p>
      
    </div>
</template>
  
  <script>
  export default {
    name: 'FooterRodape',
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
  