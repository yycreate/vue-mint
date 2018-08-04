<template>
  <div id="app">
    
    <router-view/>

  </div>
</template>

<script>
import { Header } from 'mint-ui';
export default {
  name: 'App',
  components:{
    Header
  }
}
</script>

<style>
*{
  margin:0;
  padding:0;
}
</style>
