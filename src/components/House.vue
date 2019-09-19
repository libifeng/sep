<template>
    <div>
        <h2 v-for="(item,index) in items" :key="index">{{item}}</h2>
        <h3 class="w">{{name}}</h3>
    </div>
</template>
<script>
export default {
    props:{
        name:{
           type:String,
           required:true,
           default:"太慢了"
        }
    },
    data:function(){
        return{
            items:[
                "蓝天",
                "白云",
                "绿草"
            ]
        }
    }
}
</script>
<style>
.w{
    background-color: green
}
</style>
