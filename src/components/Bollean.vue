<template>
    <div>
        <h1 class="P" v-for="(item,index) in items" :key="index">{{item}}</h1>
    </div>
</template>
<script>
export default {
    data:function(){
        return{
          items:[
              "大人",
              "小孩",
              "儿童"
          ]
        }
    }
}
</script>
