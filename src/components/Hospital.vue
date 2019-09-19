<template>
    <div>
        <h2 v-for="(item,index) in items" :key="index">{{item}}</h2>
        <h2 class="PM">{{name}}</h2>
    </div>
</template>
<script>
export default {
    props:{
        name:{
          type:String,
          required:true,
          default:"你觉得呢"
        }
    },
    data:function(){
        return{
            items:[
                "冰箱",
                "电视",
                "洗衣机"
            ]
        }
    }
}
</script>
<style>
.PM{
    background-color: aqua
}
</style>
