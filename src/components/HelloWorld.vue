<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Menu</h2>
    <ul>
      <li>
        <a
          href="#/enfance"
          target="_blank"
        >
          Enfance des frères
        </a>
      </li>
      <li>
        <a
          href="/"
          target="_blank"
        >
          Forum
        </a>
      </li>
      <li>
        <a
          href="/"
          target="_blank"
        >
          Community Chat
        </a>
      </li>
      <li>
        <a
          href="h"
          target="_blank"
        >
          Twitter
        </a>
      </li>
      <br>
      <li>
        <a
          href="/"
          target="_blank"
        >
          Docs for This Template
        </a>
      </li>
    </ul>
    <h2>gljhgljkg</h2>
    <ul>
      <li>
        <a
          href=""
          target="_blank"
        >
          vue-router
        </a>
      </li>
      <li>
        <a
          href=""
          target="_blank"
        >
          vuex
        </a>
      </li>
      <li>
        <a
          href=""
          target="_blank"
        >
          vue-loader
        </a>
      </li>
      <li>
        <a
          href=""
          target="_blank"
        >
          awesome-vue
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Helloworld',
  data () {
    return {
      msg: 'Le musée des Frères Wright'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
