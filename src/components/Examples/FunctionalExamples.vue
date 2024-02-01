<template>
<h2>:not() Class</h2>
  <p class="intro">
    This paragraph is an intro.
  </p>
  <p> Lorem Ipsum test text a lot of text whoa thats a lot of text.</p>
  <p> WOW theres still more text here where does this guy get all this text.</p>
</template>

<style scoped>
p{
  font-weight: bold;
}
.code{
  font: 1em Consolas, monospace;
  margin: auto;
  background-color: #eee;
  padding: 20px;
  width: 400px;
  text-align: left;
  border-radius: 10px;
}
/*
p:not(.intro) {
  color: #227700;
}*/
</style>