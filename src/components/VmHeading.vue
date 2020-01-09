<template>
 <component :is ="elementAAfficher">{{text}}</component>
   </template>

<script>

export default {
    name: 'VmHeading',
props:['type','text'],

computed: {
    elementAAfficher() {
        // return "h"+this.type
        return `h${this.type}`
    }
}
}
</script>

<style>

</style>