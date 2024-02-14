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


p:not(.intro) {
  color: #227700;
}
</style>