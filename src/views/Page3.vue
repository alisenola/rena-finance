<template>
  <div class="hello">
    <h1>PAGE 3</h1>
    <h1>The user is {{ $route.params.name }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Page3',
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
  color: #42b983;
}
</style>
