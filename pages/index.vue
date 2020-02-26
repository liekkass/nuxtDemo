<template>
  <section class="container">
    <div>
      <app-logo/>
      <ul>
        <li><nuxt-link  :to="{name: 'index'}">home</nuxt-link></li>
        <li><nuxt-link  :to="{name: 'about'}">about</nuxt-link></li>
        <li><nuxt-link  :to="{name: 'news', params: {nuewsId: 299}}">news</nuxt-link></li>
      </ul>
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

