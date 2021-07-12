<template>
  <div id="app">
     <Header />
     <Main />
     <Footer /> 
     <TopFooter />
 
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Main from '@/components/Main.vue'
import Footer from '@/components/Footer.vue'
import TopFooter from '@/components/TopFooter.vue'


export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
    TopFooter
  }
}
</script>

<style lang="scss">
  @import "./style/app.scss"

</style>
