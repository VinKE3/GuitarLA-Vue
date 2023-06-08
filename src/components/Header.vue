<script setup>
import { ref, reactive } from "vue";
import { db } from "../data/guitarras";
const state = reactive({
  guitarras: db,
});
console.log("guitarras", state.guitarras);
console.log(state.guitarras);
</script>
<template>
  <div></div>
</template>

<style lang="scss" scoped></style>
