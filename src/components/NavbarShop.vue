<template>
  <div id="nav-bar">
    <router-link :to="{ name: 'product' }" id="product-link">Product Page</router-link>
    <router-link :to="{ name: 'cart' }" id="cart-link"><button>Cart</button></router-link> 
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
#nav-bar {
  border-bottom: 1px solid #ddd;
  height: 75px;
  width: 100%;
}

#product-link {
  text-align: center;
  display: block;
  color: #418883;
  font-size: 22px;
  left: 32px;
  position: absolute;
  top: 16px;
  text-decoration: none;
}

#product-link h1 {
  margin: 0;
}

#cart-link {
  position: absolute;
  right: 16px;
  top: 16px;
}
</style>