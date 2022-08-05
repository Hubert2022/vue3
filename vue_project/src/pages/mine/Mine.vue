<template>
  <div class="mine">
    <div class="content">个人中心</div>
    <Footer />
  </div>
</template>                         
                                    
<script>
import { ref, reactive } from "vue";
import Footer from "../../components/Footer.vue";
export default {
  components: {
    Footer,
  },
  setup() {
    return {};
  },
};
</script>                           
                                    
<style lang='less' scoped>
.mine {
  display: flex;
  flex-flow: column;
  height: 100%;
  .content {
    flex: 1;
    overflow-y: auto;
  }
}
</style>                           