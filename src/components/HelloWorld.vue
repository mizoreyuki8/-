<script setup>
import ClickCounter from "./ClickCounter.vue";
import TODOList from "./TODOList.vue";
defineProps({
  msg: { type: String, default: "" },
});
</script>

<template>
  <div>
    <h1>{{ msg }}</h1>
    <ClickCounter />
    <TODOList />
  </div>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
