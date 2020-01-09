<template>
   <div>
      <VmBlockquote text="Mon text"></VmBlockquote>
      <VmBlockquote text="Mon autre text"></VmBlockquote>
  </div>
</template>

<script>
import VmBlockquote from './components/VmBlockquote' 

export default {
  name: 'app',
  components:{
    VmBlockquote,
  }
   
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
