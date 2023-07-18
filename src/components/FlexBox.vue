<template>
  <div
    class="box"
    v-for="i in cantidad"
    :key="i"
    :style="generarColorAleatorio()"
  >
    <span> {{ i }}</span>
  </div>
</template>

<script setup lang="ts">
defineProps({
  cantidad: {
    type: Number,
    default: 4,
  },
});
function generarColorAleatorio() {
  var color = "rgb(";
  color += Math.floor(Math.random() * 256) + ",";
  color += Math.floor(Math.random() * 256) + ",";
  color += Math.floor(Math.random() * 256) + ")";
  return { "background-color": color };
}
</script>

<style scoped>
.box {
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 20px;
  width: 100px;
  height: 100px;
}
</style>
