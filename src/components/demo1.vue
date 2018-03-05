<template>
  <div class="hello">
    <div class="test">字体大小测试</div>
  </div>
</template>

<script>
export default {
  name: 'demo1',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .hello {
    width: 1500px; 
    height: 500px; 
    background-color: aquamarine;
  }
  .test {
    font-size: 20px;
  }
</style>
