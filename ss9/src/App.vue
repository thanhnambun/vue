<template >
  <div>
    <h1>data binding</h1>
    <p> one way data binding</p>
    <p>hiển thị giá trị count :{{ count }}</p>
    <button @click="handleClick">click</button>
    <Bt1></Bt1>
    <Bt2></Bt2>
    <Bt3/>
    <Bt4/>
    <Bt5/>
    <Bt6/>
    <Bt7/>
    <Bt8/>
    <Bt9/>
    <Bt10/>
  </div>
</template>
<script setup>
import {ref} from 'vue'
import Bt1 from './components/Bt1.vue';
import Bt2 from './components/Bt2.vue';
import Bt3 from './components/Bt3.vue';
import Bt4 from './components/Bt4.vue';
import Bt5 from './components/Bt5.vue';
import Bt6 from './components/Bt6.vue';
import Bt7 from './components/Bt7.vue';
import Bt8 from './components/Bt8.vue';
import Bt9 from './components/Bt9.vue';
import Bt10 from './components/Bt10.vue';
const count = ref("0")
const handleClick =()=>{
  count.value++
}

</script>
<style >
  
</style>