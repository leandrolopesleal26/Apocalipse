<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      <i>Feliz aquele que lê as palavras desta profecia e felizes aqueles que ouvem <br>
      e guardam o que nela está escrito, porque o tempo está próximo.<br>
      Apocalipse 1:3 (NVI)</i>
      
    </p>
    <h3>Introdução ao livro de Apocalipse</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Mapa Geral</a></li> 
    </ul>
    <h3>Recursos visuais</h3>
    <ul>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">As 7 cartas as igrejas</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Abertura dos 7 selos</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">As 7 trombetas</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Os 4 cavaleiros</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">As 7 taças</a></li>
    </ul>
    <h3>Material de apoio</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
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
  color: #42b983;
}
</style>
