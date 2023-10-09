  <script>
  import Header from './components/Header.vue';
  export default {
    name: 'app',
    components:{
      Header
    },
    data(){
      return{
        paragrafo: 'ciao??'
      }
    }
  }
  </script>

<template>
  <Header />
  <h1>{{paragrafo}}</h1>
</template>

<style>

</style>