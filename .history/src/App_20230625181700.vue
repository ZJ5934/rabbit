<script setup>
import {ref } from 'vue'
const a = ref(0)
const add = () =>{
  a.value++
}
</script>

<template>
<h1>{{a}}</h1>
<button>{{}}</button>
</template>

