<template>
  <div class="hello">
    <div class="menu">
      <div class="menu-item menu-text">
        Resume
      </div>
      <div class="menu-item menu-text">
        Skating
      </div>
      <div class="menu-item menu-center menu-text">
        Project
      </div>
      <div class="menu-item menu-text">
        About
      </div>
      <div class="menu-item menu-text">
        Contact
      </div>
    </div>
    <div class="name">
      <div class="letter">
        <img src="../assets/R.png" class="letter-image">
      </div>
      <div class="letter">
        <img src="../assets/I.png" class="letter-image">
      </div>
      <div class="letter">
        <img src="../assets/C.png" class="letter-image">
      </div>
      <div class="letter">
        <img src="../assets/K.png" class="letter-image">
      </div>
      <div class="letter">
        <img src="../assets/Y.png" class="letter-image">
      </div>
    </div>
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
.name {
  display: flex;
  align-items: center;
  justify-content: center;
  vertical-align: middle;
  width: 100vw;
  height: 100vh;
}
.letter-image {
margin: 0%;
}
img{
  max-width: 100%;
}
.menu {
  display: flex;
}
.menu-item {
  flex: 1;
  text-align: center;
  color: #707070;
}
.menu-text {
  font-size: 20px;
  color: #818181;
  cursor: pointer;
  padding: 10px;
  border-bottom: 2px solid #080808;
}
.menu-text:hover {
  border-bottom: 2px solid #f4f6f8;
}
.menu-center {
  font-size: 30px;
}
</style>
  
