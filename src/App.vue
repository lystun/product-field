<template>
    <div id="app">
        <Header />
        <router-view/>
    </div>
</template>

<script>
    import Header from "./views/Header";

    export default {
        components: {
            Header,
        },
    }
</script>

<style lang="scss">
    body{
        font-family: 'Poppins', sans-serif;
    }
</style>
