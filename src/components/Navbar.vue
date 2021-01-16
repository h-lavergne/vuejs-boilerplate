<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <router-link :to="{name: 'home'}" class="navbar-brand" href="#">Vue-js Boilerplate</router-link>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav" data-toggle="collapse" data-target="#navbarNavAltMarkup">
        <router-link :to="{name: 'home'}"  class="nav-item nav-link" href="#">Home</router-link>
        <router-link :to="{name: 'about'}"  class="nav-item nav-link" href="#">About</router-link>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
}
</script>