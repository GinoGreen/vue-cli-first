<template>
  <div id="app" class="container">
    <Header/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
    
  }
}
</script>

<style>
  * {
    margin: 0;
    padding: 0;
  }

  #app {
    padding: 20px;
    height: 100vh;
    overflow: hidden;
  }

  header,
  section.content,
  footer {
    padding: 10px;
    border: 2px solid #000;
  }

</style>
