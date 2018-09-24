<template>
  <div>
    <header>
      <p class="brand">
        <router-link to="/">Nuxt.js Study</router-link>
      </p>
    </header>
    <div class="container">
      <nuxt/>
    </div>
  </div>
</template>

<style>
html {
  padding : 0;
  margin  : 0;
}
body {
  background : black;
  color      : white;
  padding    : 0px;
  margin     : 0;
  font-family: 'Robot';
}
a {
  color : #fc0;
}
a:hover {
  color : #ff0;
}
header {
  background  : #fc0;
  color       : black;
  padding     : 1px 10px;
  margin      : 0;
  font-weight : bold;
}
header p.brand a, header p.brand a:hover {
  color           : black;
  text-decoration : none;
}
div.container {
  padding : 10px 20px;
}
</style>

