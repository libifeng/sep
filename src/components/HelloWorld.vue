<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
     <one name="时间差不多了"/>
     <one phone="手机还可以"/>
     <car name="汽车"/>
      <study name="不能再错了"/>
      <house name="太慢了"/>
      <app name="马上抢救"/>
      <bank name="唉"/>
      <beef name="差不多了"/>
      <desk name="加油"/>
      <string name="服了"/>
      <bollean/>
      <hospital name="你觉得呢"/>
      <japan name="一切皆有可能"/>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
  </div>
</template>

<script>
import One from './One.vue'
import Car from './Car.vue'
import Study from './Study.vue'
import House from './House.vue'
import App from './App.vue'
import Bank from './Bank.vue'
import Beef from './Beef.vue'
import Desk from './Desk.vue'
import String from './String.vue'
import Bollean from './Bollean.vue'
import Hospital from './Hospital.vue'
import Japan from './Japan.vue'
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components:{
    One,
    Car,
    Study,
    House,
    App,
    Bank,
    Beef,
    Desk,
    String,
    Bollean,
    Hospital,
    Japan
   
   
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
