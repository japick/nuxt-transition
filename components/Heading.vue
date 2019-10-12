<template>
  <div :class="{ 'active' : (page === 'about') }">
    <transition-group name="heading" tag="h1">
      <h1>{{heading}}</h1>
    </transition-group>
  </div>
</template>

<script>
import { mapState } from 'vuex'
export default {
  computed: mapState(['page']),
  props: {
    heading: {
      type: String
    }
  }
}
</script>

<style>
.heading {
  transition: all 0.4s ease;
}
</style>