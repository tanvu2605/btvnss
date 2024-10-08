<template>
  <div :class="{'active': isActive}" :style="{ backgroundColor: backgroundColor }">
    Block
  </div>
</template>

<script>
export default {
  name: 'Exercise04',
  data() {
    return {
      isActive: true,  
      backgroundColor: 'blue', 
    };
  },
};
</script>

<style scoped>
.active {
  color: #fff;
  padding: 20px;
  width: 100px;
  text-align: center;
}
div {
  padding: 20px;
  text-align: center;
  margin: 10px;
}
</style>
