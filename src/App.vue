<template>
  <Dashboard msg="Welcome to Your Vue.js App"/>
</template>

<script>
import Dashboard from './components/Dashboard.vue'

export default {
  name: 'App',
  components: {
    Dashboard
  },
  data(){
    return{
      test: "test",
    }
  }
}
</script>

<style>

</style>
