<template>
  <div>
    <key-input class="demo-class"></key-input>
  </div>
</template>
<script>
import KeyInput from '../components/KeyInput'
export default {
  components: {
    KeyInput
  },
  data() {
    return {
    }
  },
  created() {},
  methods: {
  }
}
</script>
<style lang="less">
body{
  background: #efefef;
}
.demo-class{
  input{
    border:1px solid #ccc;
    outline: none;
    height: 30px;
    font-size: 16px;
    letter-spacing: 2px;
    padding: 0 5px;
  }
}
</style>
