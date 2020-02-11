<template>
    <div>
        <order-header></order-header>
        <div>{{msg}}</div>
        <order-footer></order-footer>
    </div>
</template>

<style></style>

<script>

    import OrderHeader from "../components/OrderHeader";
    import OrderFooter from "../components/OrderFooter";

    export default {
        name: 'cart',
        components: {OrderFooter, OrderHeader},
        data() {
            return {msg: 'cart'}
        }
    }

</script>