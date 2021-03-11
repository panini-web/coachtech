<template>
  <div id="app">
    <Header :parentText="sendText"></Header>
    <p>App.vue</p>
   </div>
  </template>
    
<script> 
import Header from "./components/Header";
export default{
 data(){
   return{
     sendText:"親コンポーネントのデータ"
   };
 },
 components:{
   Header
 }
};
</script>

<style>

</style>