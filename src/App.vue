<script>
import AppHeader from './components/AppHeader.vue';
export default {
  components: {
    AppHeader,
  }
}
</script>



<template>
  <!-- Import Header -->
  <AppHeader />

  <!-- Import Main -->
  <AppMain />

</template>

<style lang="scss">
@use './styles/general.scss' as *;
div.container-wrapped {
  width: 80%;
  border: 1px solid green;
  margin: 0 auto;
}
</style>