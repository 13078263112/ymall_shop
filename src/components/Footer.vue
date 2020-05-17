<template>
  <footer id="footer">
    <p>广州现代信息工程职业技术学院</p>
    <p>18Java-姚伟成</p>
    <p>违法和不良信息举报电话：130-7826-3112，本网站所列数据，除特殊说明，所有数据均别人测试</p>
  </footer>
</template>
<script>
  export default {
    data() {
      return {}
    }
  }
</script>
<style lang="stylus" scoped>
  #footer
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    align-items: center;
    height: 120px;
    background-color: #fff;
    margin-top: 20px;
    padding: 30px 0;
    font-size: 12px;
    p
      height: 30px;
</style>
