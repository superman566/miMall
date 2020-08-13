<template>
  <div>
    Cart
    <order-header />
    <router-view></router-view>
    <order-footer />
  </div>

</template>

<script>
import OrderHeader from '@/components/OrderHeader';
import OrderFooter from '@/components/OrderFooter';
export default {
name: "cart",
  components: { OrderFooter, OrderHeader }
};
</script>

<style scoped>

</style>
