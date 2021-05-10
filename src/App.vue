<template>
    <img class="logo" src="./assets/logo.svg">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/Home.vue'

export default {
    name: 'App',
    components: {
        HelloWorld
    }
}
</script>

<style>
body {
    margin: auto;
    background: #080c13;
    font-size: 16px;
}

#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}

.logo {
    width: 229px;
    height: auto;
}
</style>
