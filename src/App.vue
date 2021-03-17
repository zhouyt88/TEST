<template>
    <div id="app">
        <h1>11111</h1>
        <h2>22222</h2>
        <h3>33333</h3>
        <img class="logo" alt="CloudBase logo" src="./assets/cloudbase.png" />
        <img class="logo" alt="Vue logo" src="./assets/logo.png" />
        <HelloWorld msg="欢迎使用云开发 CloudBase Vue.js App" />
    </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
    name: "App",
    components: {
        HelloWorld,
    },
};
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}

.logo {
    width: 120px;
    padding: 10px;
}
</style>
