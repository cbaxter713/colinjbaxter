<template>
  <section class="container">
    <h1 class="title">This is the Bio Page</h1>
    <div class="links">
      <nuxt-link to="/" class="button--green">Home</nuxt-link>
    </div>
  </section>
</template>

<script>

</script>

<style>
  .container {
    display: block;
    max-width: 1300px;
    margin: 0 auto;
    padding: 0 20px;
  }

  .title {
    font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
    display: block;
    font-weight: 300;
    font-size: 100px;
    color: #35495e;
    letter-spacing: 1px;
  }

  .links {
    padding-top: 15px;
  }
</style>
