<template>
  <div id="app">
    <p>{{ message }}</p>
    <input v-model="message">
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello World',
    };
  },
};
</script>

<style scoped>
#app {
  font-size: 18px;
  font-family: 'Roboto', sans-serif;
  color: blue;
}
</style>
