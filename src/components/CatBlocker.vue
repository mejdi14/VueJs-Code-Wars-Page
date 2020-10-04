<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>

      This website will stay blocked till you finish at least one challenge <br> <br> <br> <br>
      <a href="https://www.codewars.com/" target="_blank" rel="noopener">CodeWars website</a>.
    </p>
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
a:link {
  background-color: #000000;
  color: white;
  margin-top: 30px;
  padding: 14px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
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
  color: #FFFFFF;
}
</style>
