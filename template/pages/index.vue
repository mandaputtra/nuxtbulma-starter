<template>
  <section class="hero has-text-centered">    
    <app-logo/>
    <div class="hero-body">
      <div class="container">
        <h1 class="title">
        {{ name }}
      </h1>
      <h2 class="subtitle">
        {{ description }}
      </h2>
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button is-medium is-outlined is-success">Documentation</a>

        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button is-medium is-outlined is-dark">GitHub</a>
      </div>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style>

</style>

