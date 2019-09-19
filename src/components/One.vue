<template>
    <div>
        <h2 v-for="(item,index) in items" :key="index">{{item}}</h2>
        <h2>{{name}}</h2>
        <h2>{{phone}}</h2>
    </div>
</template>
<script>
export default {
    props:{
     name:{
         type:String,
         required:true,
         default:"时间不多了"
     },
     phone:{
         type:String,
         required:true,
         default:"手机还可以"
     }
    },
    data:function(){
        return{
          items:[
              '雨伞',
              '雨衣',
               '雨靴'

          ]
        }
    }
}
</script>
