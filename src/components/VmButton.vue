<template>
  
   <a :class="{ 'button-outline':outline, 'button-clear':clear }"  class="button" href="#" @click="clickBtn">Default Button</a>
  
</template>

<script>
export default {
   name: 'VmButton',
   props: {
   outline:Boolean,
   clear:Boolean
    },
    method:{
       clickBtn(evenement){
          this.$emit('click',evenement);
       }
    }

}
</script>

<style>

</style>