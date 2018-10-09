<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
   
  </div>
</template>

<script>

// 暴露出去 才可以访问
export default {
  // 在开发者工具中能够看到的组件的名字(可以不写),写了之后方便调试
  name: "App",
  data:function(){
    return {
      message:'感觉自己萌萌哒'
    }
  }
};
</script>

<style>

</style>
