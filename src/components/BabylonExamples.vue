<template>

<div>
  <h3>Babylon Examples</h3>
  <canvas></canvas>
</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'BabylonExamples',
  mounted()
  {
    const canvas = document.querySelector("canva")
  }
});
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
