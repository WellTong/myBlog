<template>
  <div>
    <div v-for="(item, i) in types" :key="i" >
      {{item}}
      <icon :type="item" />
    </div>
  </div>
</template>

<script>
import Icon, { types } from "./"


export default {
  components: {
    Icon
  },
  data() {
    return {
      types
    }
  }
}
</script>

<style scoped>
.iconfont {
  font-size: 50px;
}
</style>