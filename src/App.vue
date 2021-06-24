<template>
<HeaderBar class="header"/>
<ListView class="list"/>
<FooterNavigation class="footer"/>
</template>

<script>
import FooterNavigation from './components/FooterNavigation.vue'
import HeaderBar from './components/HeaderBar.vue'

import ListView from './components/List.vue'

export default {
  name: 'App',
  components: {
    FooterNavigation,
    HeaderBar,
    ListView
  },
  methods: {

  }
}
</script>

<style>

body {
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.header {
  width: 100%;
  position: fixed;
  top: 0;
  left: 0;
}

.footer {
  width: 100%;
  position: fixed;
  bottom: 0;
  left: 0;
}

</style>
