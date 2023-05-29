<template>
     <div class="container ">
        <div class="row " >
            <div class="col-1 vh-100 " v-for="(item,index) in items" :key="index">
                <div class="test vh-100 p-2" >
                </div>
            </div>
        </div>
    </div> 
    </template>
    
    <script>

    export default {
     data(){
      return{
        items: [1,2,3,4,5,6,7,8,9,10,11,12],
        name:'you',
        counter:0,
           }
          }
    }
    </script>
    
    <style>
    .container{
      background-color: rgb(167, 210, 196);
    }
    .test{
      background-color: rgb(141, 204, 181);
    }
    </style>
    