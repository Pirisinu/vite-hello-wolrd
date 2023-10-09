<script>
export default {
  name: 'Footer',
  data(){
    return {
      titoloFooter: 'Footer da vue (importato in App.vue da Header.vue, settato con style scoped)'
    }
  }
}
</script>

<template>
  <h3>{{ titoloFooter }}</h3>
</template>

<style scoped>
  h3{
    color: red;
    text-align: start;
    margin: 60px;
  }
</style>