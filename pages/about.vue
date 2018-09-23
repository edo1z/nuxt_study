<template>
  <section class="container">
    <h1>About</h1>
    Nice to meet you.
    <router-link to="/">TOP</router-link>
  </section>
</template>

<script>
export default {
  asyncData (context) {

  },
  head () {
    return {
      title: 'About'
    }
  }
}
</script>

