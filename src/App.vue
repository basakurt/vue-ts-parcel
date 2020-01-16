<template>
  <div>
    <div id="app">{{ message }}</div>
  </div>
</template>

<script lang="ts">
export default {
  data() {
    return {
      message: "Hello Stranger!"
    };
  }
};
</script>

<style>
#app {
  font-size: 40px;
  color: #e9c10e;

}
</style>