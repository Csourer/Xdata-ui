<template>
  <div class="wrap">
    <h3>{{ msg }}</h3>

    <h2>基础组件</h2>

    <h4>标签</h4>
    <xd-tag>普通</xd-tag>
    <xd-tag type="success">success</xd-tag>
    <xd-tag type="warning" round>warning</xd-tag>
    <xd-tag type="error" round>error</xd-tag>
    <xd-tag bg-color="#fc0" color="#e0439a" border-color="#fc0">自定义颜色</xd-tag>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: `xdata-ui - 基于vue2.x，可复用UI组件`
    }
  },
  methods: {

  },
  mounted: () => {
    // alert(this.modalVisible)

  }
}
</script>

<style lang="less">

.wrap{
  margin: 10px;
}
h1,h3{
  margin: 0;
}
h3{
  font-weight: normal;
  font-size: 16px;
}
h4{
  font-weight: normal;
  font-size: 14px;
  text-align: left;
  background-color: #e9e9e9;
  padding: 10px;
}
h2{
  text-align: left;
  width: 100%;
  border-bottom: 1px dashed #ededed;
  font-size: 16px;
  height: 40px;
  line-height: 40px;
  text-indent: 10px;
  margin-top: 30px;
  margin-bottom: 0;
}

</style>
