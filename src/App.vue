<template>
  <router-view/>
  <Footer/>
</template>

<script>
import Footer from "../src/components/Footer.vue"
export default {
  components: {
    Footer
  }
}
</script>

<style>
:root {
  --gray: hsl(0, 0%, 10%);
  --red: rgb(242, 34, 34);
  --red-highlights: rgb(236, 46, 46);
}
*,
*:after,
*:before {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: "Catamaran", sans-serif;
}

/* #nav a.router-link-exact-active {
  color: #42b983;
} */
</style>
