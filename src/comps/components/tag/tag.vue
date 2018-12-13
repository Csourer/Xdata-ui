<template>
    <div
        class="xd__tag"
        :style="{backgroundColor: bgColor, color: color, 'border-color':borderColor}"
        :class="[
        'xd__tag--'+type,
        {'is-round': round}
        ]"
    >
    </div>
</template>

<script>

export default {
  name: 'xd-tag',
  props: {
    type: {
      type: String,
      default: 'default'
    },
    bgColor: {
      type: String,
      default: ''
    },
    borderColor: {
      type: String,
      default: ''
    },
    color: {
      type: String,
      default: ''
    },
    round: Boolean
  },
  methods: {
  }
}
</script>

<style scoped lang="less">

</style>
