<template>

    <div>
        <order-header></order-header>
        <router-view></router-view>
        <order-footer></order-footer>
    </div>

</template>

<style></style>

<script>

    import OrderHeader from "./../components/OrderHeader";
    import OrderFooter from "./../components/OrderFooter";

    export default {
        name: 'order',
        components: {OrderHeader, OrderFooter},
        data() {
            return {msg: 'order'}
        }
    }

</script>