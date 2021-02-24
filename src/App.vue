<template>
  <div id="app">
    <TheHeader />
    <router-view></router-view>
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue';

export default {
  name: 'App',
  components: {
    TheHeader
  }
}
</script>

<style>
body {
  margin: 0;
  font-family: 'Avenir', Arial, Helvetica, sans-serif;
  color: #234;
}

ul {
  list-style: none;
  margin: 0;
  padding: 0;
}
a {
  font-weight: bold;
  text-decoration: none;
  color: #234;
}

/* a.router-link-exact-active { */
a.router-link-active {
  color: #4b8;
}

</style>
