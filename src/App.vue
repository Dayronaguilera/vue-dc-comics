<template>
  <div id="app">
    <Header />
    <!-- prendiamo il jsons dalla funzione (comics in comics) e lo mandiamo al main-->
    <Main :comics="comics"/> 
    <TopFooter />
    <Footer /> 
    <SocialMedia />
  </div>
</template>

<script>
import Header from '@/components/Header.vue' //importiamo il header
import Main from '@/components/Main.vue' //importiamo il main
import Footer from '@/components/Footer.vue' //importiamo il footer
import TopFooter from '@/components/TopFooter.vue' //importiamo il top footer
import comicsJson from './jsons/dc-comics.json' //importiamo il jsons
import SocialMedia from '@/components/SocialMedia.vue' //importiamo il Social media



export default {
  name: 'App',
  components: { //elenchiamo i components importati!
    Header,
    Main,
    Footer,
    TopFooter,
    SocialMedia
  },
  data: function() { //creiamo un function che ci ritornera il jsons perche nn e un components!
    return {
      comics: comicsJson,
    };
  },
}
</script>

<style lang="scss">
  @import "./style/app.scss"

</style>
