<template>
  <div class="container">
    <h1>{{msg}}</h1>
  </div>
</template>

<script>
export default {
  name: 'Container',
  data() {
    return {
      msg: 'This is the container',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .container {
    width: 90%;
    padding: 2%;
  }
</style>
