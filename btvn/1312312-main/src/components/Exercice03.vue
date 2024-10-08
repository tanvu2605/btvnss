<template>
  <div>
    <input type="text" :disabled="isDisable" :placeholder="isDisable ? '' : 'Cho phép nhập'" />
    <p>isDisable={{ isDisable }}</p>
  </div>
</template>

<script>
export default {
  name: 'Exercice03',
  data() {
    return {
      isDisable: true,  
    };
  },
};
</script>

<style scoped>
input {
  padding: 5px;
  margin: 10px 0;
  width: 200px;
}
</style>
