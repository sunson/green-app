<template>
  <section class="container">
    <div>
      <logo size="medium"/>
      <div class="links">
        <nuxt-link to="/entrepreneurs" target="_blank" class="button--green">Entrepreneurs</nuxt-link>
        <nuxt-link to="/consumers" target="_blank" class="button--green">Consumers</nuxt-link>
        <nuxt-link to="/supporters" target="_blank" class="button--green">Supporters</nuxt-link>
        <nuxt-link to="/about" target="_blank" class="button--grey">About</nuxt-link>
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
.container
{
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title
{
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle
{
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links
{
  padding-top: 15px;
}
</style>
