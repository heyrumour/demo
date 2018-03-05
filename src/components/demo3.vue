<template>
  <div class="hello">
    <div class="reference">参照像素</div>
    <div class="rem1">测试1</div>
    <div class="rem2">测试2</div>
    <div class="vw">测试3</div>
  </div>
</template>

<script>
export default {
  name: 'demo3',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  html {
    font-size: 37.5px;
  }
  .hello {
    width: 100%; 
    background-color: aquamarine;
  }
  .reference {
    font-size: 37.5px;
  }
  .rem1 {
    font-size: 1rem;
  }
  .rem2 {
    font-size: 2rem;
  }
  .vw {
    font-size: 10vw;
  }
</style>
