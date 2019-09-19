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
            default:"加油"
        }
    },
    data:function(){
        return{
            items:[
                "都市",
                "情感",
                "谍战"
            ]
        }
    }
}
</script>
