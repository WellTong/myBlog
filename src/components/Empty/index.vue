<template>
  <div class="empty-container">
    <icon type="empty" />
    <p>{{text}}</p>
  </div>  
</template>

<script>
import Icon from "../Icon"

export default {
  props: {
    text: {
      type: String,
      default: '无数据'
    }
  },
  components: {
    Icon
  }
}
</script>

<style lang="less" scoped>

@import "~@/styles/var.less";
@import "~@/styles/mixin.less";

.empty-container {
  color: @gray;
  text-align: center;
  .self-center();
  .icon-container {
    font-size: 76px;
  }
}
</style>