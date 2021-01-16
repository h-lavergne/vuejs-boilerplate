<template>
  <div id="app">
    <navbar />
    <router-view class="container-fluid"/>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
export default {
  name: 'App',
  components: {
    Navbar
  }
}
</script>