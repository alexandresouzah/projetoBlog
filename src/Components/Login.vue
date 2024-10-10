<script>
</script>

<template>
<div class="container">
    <h1>Login</h1>
    <input type="email" placeholder="Email">
    <br>
    <input type="password" placeholder="Senha">
    <br>
    <button class="btnLogin">Enviar</button>
    <br>
</div>
</template>

<style scoped>
.container{
    justify-content: center;
    align-items: center;
    text-align: center;
    flex-direction: column;
    display: flex;
}
.btnLogin {
  padding: 5px; 
  background-color: #000000; 
  color: white; 
  text-decoration: none; 
  border-radius: 5px; 
}

.btnLogin:hover{
    background-color: #545454;
    cursor: pointer;
}
</style>