<template>
    <div class="hello">
      <h1>{{ msg }}</h1>
      <p>
        Nosso objetivo aqui é configurar/customizando o projeto.<br>
           
      </p>
      <h3>Instalar links conforme a necessidade do projeto.</h3>
      <ul>
        <li><a href="https://cli.vuejs.org" target="_blank" rel="noopener">Home</a></li>
        <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">Rotas</a></li>
        <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">Contatos</a></li>
        <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">Novidades</a></li>
      </ul> 
    </div>
</template>
  
  <script>
  export default {
    name: 'MenuGeral',
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
  