<template>
  <div class="wrapper">
    <TopArea />
    <ProductList />
    <Order />
 </div>
</template>

<script>
import TopArea from './TopArea'
import ProductList from './ProductList'
import Order from './Order'
export default {
    name: 'OrderConfirmation',
    components: { TopArea, ProductList, Order },
    setup() {
    }
}
</script>

<style lang="scss" scoped>
@import '../../style/viriables.scss';
@import '../../style/mixins.scss';
.wrapper{
    position: absolute;
    left: 0;
    right: 0;
    bottom: 0;
    top:0;
    background-color: #eee;
    overflow-y: scroll;
}

</style>
