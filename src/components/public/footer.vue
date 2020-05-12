<template>
<div id="foot">
    <mt-tabbar fixe="true" value="" v-model="selected">
        <mt-tab-item id="首页">
            <img slot="icon" src="../../assets/logo.png">
            首页
        </mt-tab-item>
        <mt-tab-item id="礼物">
            <img slot="icon" src="../../assets/logo.png">
            礼物
        </mt-tab-item>
        <mt-tab-item id="计划">
            <img slot="icon" src="../../assets/logo.png">
            计划
        </mt-tab-item>
        <mt-tab-item id="发现">
            <img slot="icon" src="../../assets/logo.png">
            发现
     </mt-tab-item>
</mt-tabbar>
</div>
</template>
<script>
export default {
  name: "vFooter",
  data() {
    return {
      selected: "首页"
    };
  }

}
</script>
<style scoped lang="scss">

</style>