<template>
  <header id="header">
    <router-link to="/" exact>Movie Filmes</router-link>
    <router-link tag="button" to="/salvos" exact>SALVOS</router-link>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
#header {
  display: flex;
  align-items: center;
  justify-content: space-around;
  width: 100%;
  height: 60px;
  background-color: brown;
}

#header a{
  text-decoration: none;
  font-size: 30px;
  color: #fff;
  cursor: pointer;

}

button{
  cursor: pointer;
  border: 0;
  background: #fff;
  padding: 5px 15px;
  outline: none;
  border-radius: 3px;
  font-weight: bold;
}
</style>