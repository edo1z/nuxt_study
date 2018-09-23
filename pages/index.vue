<template>
  <section class="container">
    <h1>Top Page</h1>
    <ul>
      <li><router-link to="/about">about</router-link></li>
    </ul>
  </section>
</template>

<script>
export default {
  head () {
    return {
      title: 'Toppage'
    }
  }
}
</script>

