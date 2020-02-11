<template>

    <div>
        <nav-header></nav-header>
        <router-view></router-view>
        <nav-footer></nav-footer>
    </div>

</template>

<style></style>

<script>

    import NavFooter from "../components/NavFooter";
    import NavHeader from "../components/NavHeader";

    export default {
        name: 'home',
        components: {NavFooter, NavHeader},
        data() {
            return {msg: 'vue模板页'}
        }
    }

</script>