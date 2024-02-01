<script setup>

</script>

<template>
  <h2>:hover & :active Class</h2>
  <div class="test-box"></div>
</template>

<style scoped>
.test-box {
  width: 100px;
  height: 100px;
  background-color: gray;
  margin: auto;
  border-radius: 10px;
}

.test-box:hover {
  background-color: red;
  width: 200px;
}

.test-box:active {
  background-color: blue;
  height: 200px;
}


</style>
<!-- eslint-disable -->