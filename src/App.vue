<template>
   <div>
      <VmBlockquote text="Mon text">mmmmmm</VmBlockquote>
      <VmBlockquote text="Mon autre text"></VmBlockquote>
      <VmHeading v-for="(h, index) in num" :key="index"  :type="h" :text="`Mon titre  ${h}`"></VmHeading>
  </div>
</template>

<script>
import VmBlockquote from './components/VmBlockquote' 
import VmHeading from './components/VmHeading'
export default {
  name: 'app',
  components:{
    VmBlockquote,
    VmHeading,
   
  },
  data(){
    return{
       num: ['1','2','3','4','5','6'],
    }
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
