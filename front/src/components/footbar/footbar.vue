<template>
  <div class="footbar">
    <div class="link_box">
      <a href="https://www.entanmo.com" target="_blank">En-Tan-Mo官网</a>&nbsp;|
      <a href="http://bbs.entanmo.com" target="_blank">En-Tan-Mo论坛</a>&nbsp;
    </div>
    <span>&copy;En-Tan-Mo</span>
  </div>
</template>

<script>
  export default {
    name: 'footbar',
    components: {
    }
  }
</script>

<style lang="" scoped>
  .footbar{
    min-width: 700px;
      font-size: 14px;
      position: absolute;
      left: 50%;
      bottom: 0;
      margin-left: -40%;
      border-top: 1px solid rgb(222, 222, 222);
      background-color: #fff;
      width: 80%;
      height: 80px;
  }
  .footbar span{
      display: inline-block;
      margin-top: 15px;
      color: rgb(130, 130, 130);
  }
  .link_box{
      margin-top: 20px;
      width: 100%;
      color: rgb(130, 130, 130);
  } 
  .link_box a{
      color: rgb(130, 130, 130);
  }
  .link_box p{
      display: inline-block;
  }
  @media screen and (max-width: 1441px) {
    /* 1360屏幕下 */
    .footbar{
      font-size: 10px;
      height: 67.5px;
    }
    .footbar span{
      margin-top: 9px;
    }
    .link_box{
      margin-top: 15px;
    }
  }
</style>
