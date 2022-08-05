<template>
  <div class="hello">
    <div>
      {{ msg }}
      <br />
      <svg class="icon" aria-hidden="true">
        <use xlink:href="#icon-sousuo"></use>
      </svg>
      <van-button type="primary">主要按钮</van-button>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
.hello {
  font-size: 20px;
  div {
    color: red;
  }
}
</style>
