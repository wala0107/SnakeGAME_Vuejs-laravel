<template>
  <div
    class="food"
    :style="{ top: foodCoord[1] + '%', left: foodCoord[0] + '%' }"
  ></div>
</template>
<script>
export default {
  name: "Food",
  props:{
    foodCoord: Array
  },
}
</script>
<style scoped>
.food {
  position: absolute;
  height: 10px;
  width: 11px;
  border: 2px solid white;
  z-index: 3;
  background-color: green;
}
</style>