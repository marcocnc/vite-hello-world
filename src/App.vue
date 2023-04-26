
<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default {
    name: 'App',
    components:{
        AppTitle,
        AppHero
    }
}
</script>

<template>
  <h1>Hello Vite!</h1>
  <AppTitle/>
  <AppHero/>
</template>

<style scoped>
    h1{
        color:blue;
    }
</style>