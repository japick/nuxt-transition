<template>
  <nav class="nav">
    <ul>
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/about">About</nuxt-link>
      </li>
    </ul>
  </nav>
</template>

<style>
.nav {
  display: block;
  width: 100%;
}
.nav ul {
  margin: 0;
  padding: 0;
}
.nav li {
  list-style: none;
}
</style>