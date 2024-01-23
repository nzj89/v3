<template>
  <div class="hello">
    <div class="name">
      <div class="letter">
        <img src="../assets/img/N.png" alt="">
      </div>
      <div class="letter">
        <img src="../assets/img/Z.png" alt="">
      </div>
    </div>
  </div>
</template>
  
<script>
export default {
  name: 'HomePage',
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
  width: 100w;
  margin-top: 100px;

}

.letter {
  margin: 10px;
  filter: drop-shadow(0px 0px 12px rgba(255, 255, 255, 0.192));
  max-width: 50%;
}
</style>
  