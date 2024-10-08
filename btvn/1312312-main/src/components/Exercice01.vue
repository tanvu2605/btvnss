<template>
  <div>
    <img :src="image" alt="Exercise Image" />
  </div>
</template>

<script>
export default {
  name: 'Exercice01',
  data() {
    return {
      image: 'https://example.com/path-to-image.jpg', // Đường dẫn đến hình ảnh
    };
  },
};
</script>

<style scoped>

</style>
