<template>
  <div id="app">
    <Header />
    <Home />
    <Footer />
  </div>
</template>

<script>

import Header from './components/header/header.vue';
import Footer from './components/footer/footer.vue';
import Home from './pages/home.vue';

export default {
  name: 'app',
  data(){
    return {}
  },
  components: {
    Header: Header,
    Footer: Footer,
    Home: Home
  },  
}
</script>

<style>
@import url('https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css');

</style>
