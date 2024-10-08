<template>
  <div>
   
    <h1 :id="elementId" :class="elementClass">Heading</h1>
  </div>
</template>

<script>
export default {
  name: 'Exercice01',
  data() {
    return {
      elementId: 'heading', 
      elementClass: 'heading', 
    };
  },
};
</script>

<style scoped>

.heading {
  color: blue;
}
</style>
