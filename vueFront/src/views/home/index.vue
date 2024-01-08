<template>
  <div class="wrap home" ref="editor">
    <div class="header">
      <header-top></header-top>
    </div>
    <div class="main-content">
      <div class="col col1">
        <one-col></one-col>
      </div>
      <div class="col col2">
        <two-col></two-col>
      </div>
      <div class="col col3">
        <three-col></three-col>
      </div>
    </div>
  </div>
</template>

<script>
import HeaderTop from './components/HeaderTop.vue'
import OneCol from './components/OneCol.vue'
import TwoCol from './components/TwoCol.vue'
import ThreeCol from './components/ThreeCol.vue'

export default {
  name: 'Home',
  components: { HeaderTop, OneCol, TwoCol, ThreeCol },
  data() {
    return {

    }
  },
  computed: {

  },
  created() {
  },
  mounted() {
    screenSize(this.$refs.editor);
  },
  methods: {

  }
}
</script>

<style lang="scss" scoped>
.wrap {
  transform-origin: 0px 0px 0px;
  background: url(../../assets/img/bg116.png) no-repeat;
}
.home {
  display: grid;
  grid-template-rows: 10vh 90vh;
  .header {
    padding: 10px;
    text-align: center;
  }
}
.main-content {
  display: grid;
  width: 100vw;
  height: 90vh;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 16px;
  .col {
    padding: 20px;
    border: 1px solid #ccc;
    text-align: center;
  }
}
</style>