<template>
  <div class="HeaderBar">
    <nav>
        <h1>Day Style</h1>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'HeaderBar',
  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

nav {
    background-color: rgb(29, 29, 29);
    height: 3em;
    margin-bottom: 0;
    text-align: center;
}

nav h1 {
  margin: 0 0 0 0;
}

.appImage {
  height: 3em;
  position: relative;
  left: 0;
  right: 100;
}

.leftButton {
 margin-right: 1em;
}



</style>
