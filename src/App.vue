<template>
  <SideBar />
  <div id="main-container">
    <Banner />
    <About />
    <Resume />
    <Portfolio />
    <Footer />
  </div>
</template>

<script>
import './style/global.css'
import SideBar from './components/SideBar.vue'
import Banner from './components/Banner.vue'
import About from './components/About.vue'
import Resume from './components/Resume.vue'
import Portfolio from './components/Portfolio.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components:{
    SideBar,
    Banner,
    About,
    Resume,
    Portfolio,
    Footer
  }
}
</script>

<style scoped>
  #main-container{
    position: absolute;
    left: 150px;
  }
  #about{
    height: 1000px;
  }
</style>