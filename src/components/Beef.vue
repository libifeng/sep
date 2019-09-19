<template>
    <div>
        <h2 v-for="(item,index) in items" :key="index">{{item}}</h2>
        <h1>{{name}}</h1>
    </div>
</template>
<script>
export default {
    props:{
        name:{
            type:String,
            required:true,
            default:"差不多了"
        }
    },
    data:function(){
        return{
            items:[
                "牛奶",
                "鸡蛋",
                "面包"
            ]
        }
    }
}
</script>
