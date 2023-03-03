<template>
  <button openType="share">点我分享</button>
</template>

<script lang="ts" setup>
import Taro, {useShareAppMessage} from "@tarojs/taro";
useShareAppMessage(() => {
  return {
    title: '测试',

    // path: `/pages/shop/detail/index?id=${shop.value.id}`
  }
})


</script>

<style lang="less">

</style>
