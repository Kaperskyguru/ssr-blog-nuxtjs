<template>
  <div>
    <section class="hero is-medium is-primary is-bold">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">Welcome to the SSR-Blog</h1>
          <h2 class="subtitle">Hope you will like it</h2>
        </div>
      </div>
    </section>

    <posts />
  </div>
</template>

<script>
import Posts from "~/components/Posts.vue";

export default {
  head: {
    title: "Home"
  },
  components: {
    Posts
  }
};
</script>

