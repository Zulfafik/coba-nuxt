<template>
  <div class="container">
    <h1>Welcome !</h1>
    <div class="card">
      <p>Sign in with</p>
      <div class="buttonLogo">
        <a href="/login"><img :src="require('~/assets/images/logo.png')" /></a>
      </div>
    </div>
  </div>
</template>
<script></script>
<style>
h1 {
  color: aliceblue;
}
.container {
  margin: 0;
  padding: 50px;
  font-family: "Verdana", sans-serif;
  text-align: center;
  background-color: brown;
}
.card {
  width: 440px;
  padding: 20px;
  background-color: rgb(255, 255, 255);
  border-radius: 15px;
}
.buttonLogo {
  width: 200px;
  box-shadow: 2px 2px 8px;
  border-radius: 15px;
}
</style>
