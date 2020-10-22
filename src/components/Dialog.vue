<template>
  <div class="dialog">
    <div
      v-for="(item, id) in dialog"
      :key="id">
      <p>{{item}}</p>
    </div>
  </div>
</template>

<script>

export default {
  props: {
    dialog: {
      type: Array,
      required: true
    }
  }
}
</script>

<style lang="scss" scoped>
.dialog {
  text-align: start;
  margin: 150px 0 150px 40vw;
  color: #ffffff;
  letter-spacing: 8px;
  display: inline-block;
}
</style>
