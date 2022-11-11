<template>
    <router-view/>
</template>

<script>
export default {
    name: 'App',
    components: {}
}
</script>

<style lang="scss">
* {
    color: $black;
    font-family: "Roboto", sans-serif;
    box-sizing: border-box;
    margin: 0 !important;
}

body {
    background-color: $white;
    padding: 16px;
}
</style>
