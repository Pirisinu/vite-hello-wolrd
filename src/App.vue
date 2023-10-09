  <script>
  import Header from './components/Header.vue';

  import Footer from './components/Footer.vue';

  export default {
    name: 'App',
    components:{
      Header,
      Footer
    },
    data(){
      return{
        paragrafo: 'lorem ipsum dolor sit amet, consectetur adip occum nost (Paragrafo generato direttamente in App.vue)'
      }
    }
  }
  </script>

<template>
  <Header />
  <p>{{paragrafo}}</p>
  <Footer />
</template>

<style >
 *{
  text-align: center;
 }
</style>