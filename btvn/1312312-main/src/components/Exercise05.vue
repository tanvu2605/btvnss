<template>
  <div>
    <button @click="handleClick">Click me</button>
  </div>
</template>

<script>
export default {
  name: "Exercise05",
  methods: {
    handleClick() {
      console.log("Clicked");
    }
  }
};
</script>

<style scoped>
</style>
