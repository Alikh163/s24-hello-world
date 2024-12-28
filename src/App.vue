<script setup>
   import { ref } from "vue";
import HelloWorld from "./components/HelloWorld.vue";
const name = ref("");


</script>


<template>
  <input v-model="name" type="text">
<div class="hi">hi {{ name }}</div>
<HelloWorld/>
</template>

<!-- <style>
.hi {
  border: solid 1px rgb(216, 213, 24);
  border-radius: 10px;
  padding-left: 10px;
  color: rgb(8, 14, 8);
  background: yellow;
}
</style> -->