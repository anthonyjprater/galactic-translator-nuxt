<template>
  <div>
    <Header />
    <Translator />
    <Footer />
  </div>
</template>

<script>

export default {
  name: 'TranslatorApp',
  head: {
    title: 'Galactic Translator App',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Home page description'
      }
    ]
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
  body {
    background-color: #000;
  }
</style>
