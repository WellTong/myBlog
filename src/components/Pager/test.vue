<template>
  <pager :current="current" :total="total" @pageChange="handleChange" />
</template>

<script>
import Pager from "./"
export default {
  components: {
    Pager
  },
  data() {
    return {
      current: 1,
      total:302
    }
  },
  methods: {
    handleChange(n) {
      this.current = n
      console.log(n);
    }
  }
}
</script>

<style>

</style>