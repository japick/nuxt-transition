<template lang="html">
  <div v-if="loading" class="PageTransition">
    <div :class="['PageTransition__background', {'anim-in': animIn}, {'anim-out': animOut}]" />
    <div :class="['PageTransition__logo', {'anim-in': animIn}, {'anim-out': animOut}]">
      Six
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    loading: false,
    animIn: false,
    animOut: false
  }),
  methods: {
    start () {
      this.loading = true
      this.animIn = true
    },
    finish () {
      setTimeout(() => {
        this.animIn = false
        this.animOut = true
      }, 1200)
      setTimeout(() => {
        this.loading = false
        this.animOut = false
      }, 2000)
    }
  }
}
</script>