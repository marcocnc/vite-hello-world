
<script>
import AppTitle from './components/AppTitle.vue'

export default {
    name: 'App',
    components:{
        AppTitle
    }
}
</script>

<template>
  <h1>Hello Vite!</h1>
  <AppTitle/>
</template>

<style scoped>
    h1{
        color:blue;
    }
</style>