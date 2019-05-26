<template>
  <section class="container">
    <div>
      <logo />
      <h1 class="title">
        Nuxt w/ Vue Material
      </h1>
      <h2 class="subtitle">
        Simple boilerplate for a nuxt and vue-material project
      </h2>
      <div class="links">
        <md-button href="https://nuxtjs.org/" target="_blank" class="md-raised md-primary">
          Documentation
        </md-button>

        <md-button href="https://github.com/nuxt/nuxt.js" target="_blank" class="md-raised md-accent">
          GitHub
        </md-button>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
  line-height: 110px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
  line-height: 42px;
}

</style>
