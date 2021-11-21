<template>
  <div id="app">
    <div id="nav">
      <div>
        <img src="./assets/building.png" alt="building image" width="500px" height="500px">
      </div>
      <vue-typer :text='description' erase-style='backspace'></vue-typer>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      description: `Hi everyone, I'm Cristopher Zaiz and I am building my portfolio.`
    }
  }
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
