<template>
  <div class='fadein'>
    <Header />
    <Startsite />
    <Introduce />
    <Black />
    <Foods />
    <Black />
    <Cultures />
    <Member />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Startsite from './components/Startsite.vue'
import Black from './components/Black.vue'
import Introduce from './components/Introduce.vue'
import Foods from './components/Foods.vue'
import Cultures from './components/Cultures.vue'
import Member from './components/Member.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Startsite,
    Black,
    Introduce,
    Foods,
    Cultures,
    Member,
    Footer
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
}
.fadein {
  animation: fadein 1s;
}
@keyframes fadein {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>
