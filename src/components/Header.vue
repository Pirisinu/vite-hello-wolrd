<script>
export default {
  name: 'Header',
  data(){
    return{
      titolo: 'Titolo da vue (importato in App.vue da Header.vue, settato con style scoped)'
    }
  }
}
</script>

<template>
  <h1>{{ titolo }}</h1>
</template>

<style scoped>
    h1{
    color: blue;
    text-align: center;
  }
</style>