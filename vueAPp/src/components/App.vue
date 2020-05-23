<template>
  <div id="app">
      <Header/>
      <router-view/>
  </div>
</template>

<script>

import Header from './layout/Header';
export default {
  name:"app",
  components:{
    Header
  }
}
</script>

<!-- Global CSS -->
<style>
  .btn{
    display: inline-block;
    border: none;
    background: #555;
    color: #fff;
    padding: 7px 20px;
    cursor: pointer;
  }

  .btn:hover{
    background: #666;
  }
</style>
