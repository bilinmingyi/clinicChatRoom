<!-- 组件 没有数据的组件 -->
<template>
  <div class="without-data">{{withoutContent}}</div>
</template>
<script>
export default {
  props: {
    withoutContent: {
      type: String,
      default: "没有相关记录"
    }
  },
  name: 'blmyWithoutData'
}
</script>

<style lang="scss" scoped>
.without-data {
  background: $bgwhite2;
  color: $gray2;
  height: 88px;
  line-height: 88px;
  width: 100%;
  margin-top: 30px;
  text-align: center;
  font-size: 30px;
  margin-bottom: 30px;
}
</style>
