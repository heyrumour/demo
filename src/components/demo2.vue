<template>
  <div class="hello">
    <div class="p1">              
      <div class="s1">111</div>  
      <div class="s2">222</div>
    </div>
    <div class="p2">
      <div class="s3">333</div>
      <div class="s4">444</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'demo2',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .p1 {font-size: 16px; line-height: 32px;}
  .s1 {font-size: 2em;}
  .s2 {font-size: 2em; line-height: 2em;}

  .p2 {font-size: 16px; line-height: 2;}
  .s3 {font-size: 2em;}
  .s4 {font-size: 2em; line-height: 2em;}

  .hello {
    width: 100%; 
    height: 500px; 
    background-color: aquamarine;
  }

</style>
