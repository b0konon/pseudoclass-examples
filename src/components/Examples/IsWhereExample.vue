<script setup>

</script>

<template>
<h2>:is() & :where() Class</h2>
  <article>
    <h3>:is()-styled links</h3>
    <section class="is-class">
      <p>
        Here is my main content. This
        <a href="https://mozilla.org">contains a link</a>.
      </p>
    </section>

    <aside class="is-class">
      <p>
        Here is my aside content. This
        <a href="https://developer.mozilla.org">also contains a link</a>.
      </p>
    </aside>

    <footer class="is-class">
      <p>
        This is my footer, also containing
        <a href="https://github.com/mdn">a link</a>.
      </p>
    </footer>
  </article>

  <article>
    <h3>:where()-styled links</h3>
    <section class="where-class">
      <p>
        Here is my main content. This
        <a href="https://mozilla.org">contains a link</a>.
      </p>
    </section>

    <aside class="where-class">
      <p>
        Here is my aside content. This
        <a href="https://developer.mozilla.org">also contains a link</a>.
      </p>
    </aside>

    <footer class="where-class">
      <p>
        This is my footer, also containing
        <a href="https://github.com/mdn">a link</a>.
      </p>
    </footer>
  </article>
  <div class="code">
    :is() > simple selector > :where()
  </div>
</template>

<style scoped>
:is(section.is-class, aside.is-class, footer.is-class) a{
  color: #270;
  font-weight:bold;
}

:where(section.where-class, aside.where-class, footer.where-class) a{
  color: #027;
  font-weight:bolder;
}
/*
footer a {
  color: #f27;
  font-weight: bold;
}*/



.code{
  font: 1em Consolas, monospace;
  margin: auto;
  background-color: #eee;
  padding: 20px;
  width: 400px;
  text-align: center;
  border-radius: 10px;
}
</style>