<template>
  <section class="container">
    <Header />
    <div class="content">
      <h2 class="italic">
        HERE IS AN ITALIC TITLE YO
      </h2>
      <p>This is a test of the emergency broadcast system.</p>
      <div class="links">
        <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation</a>
        <a href="https://github.com/nuxt/nuxt.js" target="_blank" class="button--grey">GitHub</a>
      </div>
    </div>
  </section>
</template>

<script>
import Header from '~/components/Header.vue'

export default {
  components: {
    Header
  }
}
</script>
