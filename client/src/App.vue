<template>
  <div id="app">
    <img alt="Vue logo" src="https://scontent.fceb2-1.fna.fbcdn.net/v/t1.0-9/59121137_1245549572261179_3032959295726551040_n.jpg?_nc_cat=111&ccb=2&_nc_sid=09cbfe&_nc_ohc=DeCphvp2oSYAX_w2UHn&_nc_oc=AQlJMH4mkptPD1IQXFyAPw-ogBRx-1wAtT9XdEP1VLO9MeCs6RioVdIpSwTOymqh8O0KgSC414WOztn_b6p1T0ar&_nc_ht=scontent.fceb2-1.fna&oh=f36951dddee8046e2aba26f93b3b0faf&oe=5FCBC8F2">
    <PostComponent />
  </div>
</template>

<script>
import PostComponent from './components/PostComponent.vue'

export default {
  name: 'App',
  components: {
    PostComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
