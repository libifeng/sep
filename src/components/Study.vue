<template>
    <div>
        <h2 v-for="(item,index) in items" :key="index">{{item}}</h2>
        <h3>{{name}}</h3>
    </div>
</template>
<script>
export default {
    props:{
        name:{
            type:String,
            required:true,
            default:"不能再错了"
        }
    },
    data:function(){
        return{
            items:[
                "树叶",
                "树根",
                "树茎"
            ]
        }
    }
}
</script>
