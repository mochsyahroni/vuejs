<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Menu</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Kategory</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Kritik&Saran</a></li>
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
ul {
  list-style-type: none;
  padding: 0;
  background: yellow;
  height: 25px;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
