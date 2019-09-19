<template>
    <div>
        <h2 v-for="(item,index) in items" :key="index">{{item}}</h2>
        <h3>{{name}}</h3>
    </div>
</template>
<script>
export default {
  props: {
    name: {
      type: String,
      required: true,
      default: "马上抢救"
    }
  },
  data: function() {
    return {
      items: ["坚持", "努力", "不放弃"]
    };
  }
};
</script>
