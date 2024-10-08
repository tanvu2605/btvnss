<template>
  <div>
    <button @click="handleClick('Rikkei Academy')">Get param</button>
  </div>
</template>

<script>
export default {
  name: "Exercise06",
  methods: {
    handleClick(param) {
      console.log(param);
    }
  }
};
</script>

<style scoped>
</style>
