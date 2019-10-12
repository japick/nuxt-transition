<template>
  <section class="container">
    <Nav />
    <h1 class="heading">Home</h1>
    <img src="~/assets/img/essence_home2-872x570.jpg" alt="#">
  </section>
</template>

<script>
import Nav from '~/components/Nav'
import Heading from '~/components/Heading'
export default {
  components: {
    Nav,
    Heading
  }
}
</script>

<style>

.container {
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  overflow: hidden;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
