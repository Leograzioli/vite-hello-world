<script>
import AppJumbo from "./components/AppJumbo.vue";

export default {
  data() {
    return {
      greeting: "my first vite vue page "
    }
  },
  components: {
    AppJumbo
  },
}
</script>

<template>
  <AppJumbo />
  <div> {{ greeting }}</div>
</template>

<style>

</style>