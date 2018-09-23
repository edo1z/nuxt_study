<template>
  <div class="container">
    <h1 v-if="error.statusCode === 404">404 Not Found</h1>
    <h1 v-else>Error!</h1>
    <nuxt-link to="/">ホーム</nuxt-link>
  </div>
</template>
<script>
export default {
  props: ['error'],
  layout: 'error_layout',
  head () {
    return {
      title: 'Error'
    }
  }
}
</script>
