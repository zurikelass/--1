<script>
import List from './List.vue'
  export default{
    components:{
      List
    },
    data(){
      return{
        pageTitle:"My first vue",
        data: [
         {
          id:1,
          title: "Menu"
         },
         {
          id:2,
          tittle: "Contact"
         } ,
        {
          id:3,
          tittle: "About Us"
        },
        ]
      }
    
    } 
    
  }
</script>
<template>
  <h1>{{pageTitle}}</h1>
  <List :data="data"/>
</template>
