<template>
  <div class="home">
    <top-bar></top-bar>
    <header-nav></header-nav>
  </div>
</template>

<script>
// @ is an alias to /src
import topBar from '@/components/topBar'
import headerNav from './components/header.vue'

export default {
  name: 'Home',
  components: {
    topBar,
    headerNav
  }
}
</script>
