<template>
    <div>
        <h2 v-for="(item,index) in items" :key="index">{{item}}</h2>
        <h2 class="M">{{name}}</h2>
    </div>
</template>
<script>
export default {
  props:{
    name:{
      type: String,
      required: true,
      default: "汽车"
    }
  },
  data: function() {
    return {
      items: ["迅速", "赶紧", "速度"]
    };
  }
};
</script>
<style>
.M{
    background-color: red
}
</style>
