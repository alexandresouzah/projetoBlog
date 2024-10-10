<script>
import router from '@/router/index.js';
</script>

<template>
<div class="Cabecalho">
    <img src="../assets/logotipo.png" class="logotipo">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/Login">Login</RouterLink>
</div>
</template>

<style scoped>
.logotipo{
  border-radius: 10px;
  width: 110px;
  height: 60px;
}

img{
  height: 70px;
  width: 100px;
}

.Cabecalho {
  height: 80px;
  width: 100%;
  background-color: black;
  position: relative;
  display: flex; 
  align-items: center; 
  padding: 1rem; 
  border-radius: 15px 15px 0px 0px;
}

.links {
  display: flex; 
  margin-left: 1rem; 
  color: white;
  text-decoration: none;
  transition: 0.4s;
  padding: 3px;
}

</style>