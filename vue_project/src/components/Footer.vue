<template>
  <div class="footer">
    <div class="item">
      <router-link to="/home" active-class="nav_color">
        <van-icon name="wap-home-o" class="nav_item" size='30'/>
        首页
      </router-link>
    </div>
    <div class="item">
      <router-link to="/cart" active-class="nav_color">
        <van-icon name="shopping-cart-o" class="nav_item" size='30'/>
        购物车
      </router-link>
    </div>
    <div class="item">
      <router-link to="/order" active-class="nav_color">
        <van-icon name="orders-o" class="nav_item" size='30' />
        订单
      </router-link>
    </div>
    <div class="item">
      <router-link to="/mine" active-class="nav_color">
        <van-icon name="friends-o" class="nav_item" size='30'/>
        我的
      </router-link>
    </div>
  </div>
</template>                         
                                    
<script>
import { ref, reactive } from "vue";
export default {
  setup() {
    return {};
  },
};
</script>                           
                                    
<style lang='less' scoped>
.footer {
  display: flex;
  font-size: 14px;
  background-color: #fff;
  border-top: 0.5px solid #eee;
  .item {
    flex: 1;
    display: flex;
    justify-content: center;
    .nav_item {
      display: flex;
      flex-flow: column;
      align-items: center;
    }
    .nav_color{
      color: #ffc400;
    }
  }
}
</style>                            