<template>
  <section class="container">
    <Nav />
    <h1 class="heading">About</h1>
    <img src="~/assets/img/michael_elliott_thumbnail_01-871x570.jpg" alt="#">
  </section>
</template>

<script>
import Nav from '~/components/Nav.vue'
import Heading from '~/components/Heading'
export default {
  components: {
    Nav,
    Heading
  }
}
</script>

