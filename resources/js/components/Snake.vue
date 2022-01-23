<template>
  <div
    class="body"
    :style="{ top: snakeDot[1] + '%', left: snakeDot[0] + '%' }"
  ></div>
</template>
<script>
export default {
  name: "Snake",
  
  props: { snakeDot: Array },
  
  
};
</script>
<style scoped>
.body {
  position: absolute;
  height: 10px;
  width: 11.4px;
  border: 2px solid white;
  z-index: 3;
  background-color: red;
}
</style>