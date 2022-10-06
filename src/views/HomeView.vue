<script setup lang="ts"></script>

<template>
  <section>
    <article>
      <h2 class="h1">Cast Iron Dev</h2>
      <p>Husband &mdash; Father &mdash; Developer &mdash; Cast Iron Fan</p>
    </article>
  </section>
</template>

<style scoped lang="scss">
section {
  height: 100vh;
  width: 100vw;
  display: grid;
  grid-template-columns: 4fr 3fr 4fr;
  grid-template-rows: 4fr 3fr 4fr;
  background: url(/src/assets/images/home_large.jpg) no-repeat center/cover;

  article {
    text-align: center;
    grid-column-start: 2;
    grid-row-start: 2;
    background-color: #eee;
    border-radius: 0px 10px 0px 10px;
    box-shadow: 0px 0px 0px 2px #333;
  }
}
</style>
