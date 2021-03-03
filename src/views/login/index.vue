<template>
<div id="login">
    <el-button @click="drawer = true" type="primary" style="margin-left: 16px;">
  点我打开
</el-button>
<el-drawer
  title="我是标题" :visible.sync="drawer" :with-header="false">
  <span>我来啦!</span>
</el-drawer>

</div>
</template>

<script>
export default {
  components:{},
  props:{},
  data(){
    return {
      drawer: false,
    };
  },
  watch:{},
  computed:{},
  methods:{},
  created(){},
  mounted(){}
};
</script>
<style lang="scss" scoped>
</style>

