<template>
  <div>
    <div>我是AboutChild子路由Two页面</div>
    <div class="father">
      <img
        src="http://img2.imgtn.bdimg.com/it/u=2055680573,3089421073&fm=26&gp=0.jpg"
        alt=""
      />
      <div class="zedang"></div>
    </div>
  </div>
</template>

<script>

</script>
<style lang="less">
.father {
  position: relative;
  filter:blur(2px);
  .zedang {
    position: absolute;
    width: 200px;
    height: 200px;
    top: 0;
    z-index: 999;
    background:gray;
    opacity: 0.4;
  }
}
</style>
