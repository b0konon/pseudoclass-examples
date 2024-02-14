<template>
  <h2>:has() Class</h2>
  <h2> This Heading has a paragrah</h2>
  <p> Wow what a paragraph im paragraphing real hard right now. </p>
</template>

<style scoped>

h2:has(+ p) {
  color: red;
}
</style>