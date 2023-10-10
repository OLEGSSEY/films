<template>
  <Header />
  <router-view/>
</template>

<script>
import Header from './components/UI/Header/v-header.vue'

export default {
  components: {
    Header
  }
}
</script>

<style>
@import url(./App.css);
</style>
