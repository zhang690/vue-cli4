<template>
  <div>
    <button @click="goAbout">跳转到about页面</button>
  </div>
</template>
<script>
// import axios from 'axios';
export default {
  methods:{
    goAbout(){
      this.$router.push('./About')
    }
  }
};
</script>
<style lang="less"></style>
