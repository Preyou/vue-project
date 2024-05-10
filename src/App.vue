<script setup>
import VueChart from 'vue-echarts'
import {ref} from 'vue'
import HelloWorld from './components/HelloWorld.vue'

const a = ref()
console.log(a);

const b = ref()
console.log(b);
</script>

<template>
  <VueChart ref="a"></VueChart>
  <HelloWorld ref="b" />
</template>
