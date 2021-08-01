<template>
  <div class="under-construction">
    <img alt="VL Temp Logo" src="../assets/logo.png">
    <h1 class="construction-msg">{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'VerilianLabs',
  data () {
    return {
      msg: "[ UNDER CONSTRUCTION ]"
    }
  }
}


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin-top: 60px;
}
h3 {
  margin: 40px 0 0;
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
.under-construction{
  margin-top: 100px;
}
.construction-msg {
  font-size: 24pt;
}
@media screen and (max-width: 480px) {
  .construction-msg {
    font-size: 16pt;
  }
}
</style>
