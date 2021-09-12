<template>
  <div class="banner">
    <empty/>
  </div>
</template>

<script>
import Empty from './'

export default {
  components: {
    Empty
  }
}
</script>

<style lang="less" scope>
.banner {
  width: 500px;
  height: 500px;
  position: absolute;
  border: 2px solid black;
}

</style>