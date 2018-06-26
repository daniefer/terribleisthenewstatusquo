<template>
  <div class="layout">
    <div class="banner">
        <img src="./assets/first-terrible-thing.png">
        <h1>{{ msg }}</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Comming Suun'
    }
  }
}
</script>

<style>
.layout {
  display: grid;
  grid-template-columns: 40px auto 40px;
  grid-template-rows: 40px auto 40px;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #f67280;
  background-color: #6c5b7b;
  height: 100vh;
}

.banner {
  display: flex;
  grid-column: 2;
  grid-row: 2;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

h1, h2 {
  font-weight: normal;
  font-family: 'Papyrus';
  font-weight: bold;
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

img {
  width: 50%;
}
</style>
