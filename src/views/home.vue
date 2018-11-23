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
      msg: `xdata-ui - 基于vue2.x，可复用UI组件`,
      value: '',
      value1: '',
      value2: '',
      value3: '',
      inputValue: '',
      modalVisible1: false,
      modalVisible2: false,
      modalVisible3: false,
      zIndex: 3000,
      stepList: ['发起工单', '主管审批', '经理审批', '总监核查', '结束'],
      step: 2,
      tag1: true,
      switch1: true,
      switch2: false,
      curSelected: '3',
      inputVal: '',
      textareaVal: '',
      selectVal: '',
      switchVal: true,
      radio: '巴士',
      checkbox: ['1', '4'],
      hrefObj: { path: '/mall', params: { userId: 123 } },
      actionSheetVisible1: false,
      actionSheetVisible2: false,
      popupVisible1: false,
      popupVisible2: false,
      active: '/mall'
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
.btn__group{
  border: 1px solid #eee;
  padding: 10px;
  position: relative;
  margin: 0 20px;
}
.btn__group::before{
  content: '按钮组';
  font-size:12px;
  position: absolute;
  top: -6px;
  right: -20px;
  background: #fff;
  color: #aaa;
}
.btn__block{
  margin: 0 auto!important;
}
.wrap > .xd__btn,.xd__tag{
  margin-bottom: 10px;
}

</style>
