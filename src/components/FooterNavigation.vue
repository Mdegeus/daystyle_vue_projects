<template>
  <div class="Footer">
    <nav>
        <button class="leftButton">Home</button>
        <button>Custom</button>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'FooterNavigation',
  props: {
    
  },
  methods: {
    LoadPage () {

    }   
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
}

.leftButton {
 margin-right: 1em;
}

button {
 border: none;
 padding: 1em 15% 1em 15%;
 margin-top: .22em;
 background-color: transparent;
 color: rgb(15, 161, 219);
 font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

button:hover {
    color: greenyellow;
}



</style>
