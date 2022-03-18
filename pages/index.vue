<template>
  <div class="global-container">
    <div class="belakang"></div>
    <div class="belakang2"></div>
    <div class="container">
      <div class="menu">
        <h1 class="text-center welcome">Welcome !</h1>
        <div class="div-center text-center kotak">
          <b-card-text>Sign in with</b-card-text>
          <b-button class="tombol" href="/login" variant="light">
            <img src="~/assets/images/logo.png" alt="" />
          </b-button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
<style>
html,
body {
  height: 100%;
}
.container {
  height: 600px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.menu {
}
.welcome {
  color: rgb(255, 255, 255);
  margin-bottom: 60px;
}
.kotak {
  background-color: rgb(255, 255, 255);
  width: 440px;
  padding: 25px;
  border-radius: 10px;
}
.tombol {
  box-shadow: 2px 2px 8px rgb(190, 190, 190);
  border-radius: 10px;
}
.belakang {
  height: 350px;
  width: 100%;
  background-image: linear-gradient(to right, #c43235, #f79fa1);
  position: absolute;
  z-index: -1;
}
.belakang2 {
  height: 100%;
  width: 100%;
  background-color: #464646;
  position: absolute;
  z-index: -2;
}
</style>
