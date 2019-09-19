<template>
    <div>
        <h2 v-for="(item,index) in items" :key="index">{{item}}</h2>
        <h1 class="A">{{name}}</h1>
    </div>
</template>
<script>
export default {
    props:{
        name:{
            type:String,
            required:true,
            default:"唉"
        }
    },
    data:function(){
        return{
            items:[
                "紧急",
                "救援",
                "等待"
            ]
        }
    }
}
</script>
<style>
.A{
    background-color: yellow
}
</style>
