<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <one/>
    <car/>
    <study/>
   <house/>
   <app/>
   <bank/>
   <beef/>
   <desk/>
   <string/>
   <bollean/>
   <hospital/>
   <Japan/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import One from '@/components/One.vue'
import Car from '@/components/Car.vue'
import Study from '@/components/Study.vue'
import House from '@/components/House.vue'
import App from '@/components/App.vue'
import Bank from '@/components/Bank.vue'
import Beef from '@/components/Beef.vue'
import Desk from '@/components/Desk.vue'
import String from '@/components/String.vue'
import Bollean from '@/components/Bollean.vue'
import Hospital from '@/components/Hospital.vue'
import Japan from '@/components/Japan.vue'
export default {
  name: 'home',
  components: {
    HelloWorld,
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
