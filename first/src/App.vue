<template>
    <div id="app">
      <cover msg="anjay"/>
    </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import cover from './components/cover.vue'

export default {
  name: 'App',
  components: {
    cover
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Chivo&family=Dynalight&display=swap');
#app{
  font-family: Dynalight, Chivo;
  text-align: center;
  color: black;
  margin-top: 6rem;
}

</style>
