<template>
    <div>
        <h2 v-for="(item,index) in items" :key="index">{{item}}</h2>
        <h1 class="M">{{name}}</h1>
    </div>
</template>
<script>
export default {
    props:{
        name:{
        type:String,
        required:true,
        default:"服了"
        }
    },
    data:function(){
        return{
            items:[
                "雷管",
                "炸药",
                "导火索"
            ]
        }
    }
}
</script>
<style>
.M{
    background-color: blueviolet
}
</style>
