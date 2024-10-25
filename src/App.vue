<template>
  <div>{{demo}}</div>
  <Loading msg='Loading...' :duration='5000' />
</template>

<script lang='ts' setup>
import { ref } from 'vue';
import Loading from './components/Loading.vue'


const demo = ref('demo')
</script>

<style scoped>
#app, body {
  width: 100vw;
  height:100vh;
}
</style>
