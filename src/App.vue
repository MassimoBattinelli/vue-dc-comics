<template>
  <div id="app">
    <!-- Componente header -->
    <Header/>
    <main>
      <!-- Componente comics -->
      <Comics/>
    </main>
    <!-- Componente Footer -->
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Comics from './components/Comics.vue'

export default {
  name: 'App',
  components: {
    Header,
    Comics,
    Footer
  }
}
</script>

<style lang="scss">
// general rules
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

// container generale
.ms-container {
  display: flex;
  width: 67%;
  margin: 0 auto;
}

</style>
