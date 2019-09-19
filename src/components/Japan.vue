<template>
    <div>
        <h1 v-for="(item,index) in items" :key="index">{{item}}</h1>
        <h1 class="PM">{{name}}</h1>
    </div>
</template>
<script>
export default {
    props:{
        name:{
            type:String,
            required:true,
            default:"一切皆有可能"
        }
    },
    data:function(){
        return{
            items:[
             "衣服",
             "鞋子",
             "帽子"
            ]
        }
    }
}
</script>
<style>
.PM{
    background-color: aquamarine
}
</style>
