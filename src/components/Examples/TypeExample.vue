<template>
<h2>:nth-of-type() Class</h2>
<div class="wrapper">
  <div>Dieter Div</div>
  <span>Sabine Span</span>
  <div>Detlef Div</div>
  <div>Dunya Div</div>
  <span>Stefan Span</span>
</div>
</template>

<style scoped>
.wrapper{
  font-weight: bold;
}
/*
.wrapper span:nth-of-type(2) {
  font-size: 2rem;
  color: red;
}
*/
.wrapper div:last-of-type {
  font-size: 2rem;
}

</style>