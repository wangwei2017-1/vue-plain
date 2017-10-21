
<template>
  <nav class="navbar navbar-default">
    <div class="container-fluid">
      <div class="navbar-header">
        <a class="navbar-brand" href="#">
          <i class="glyphicon glyphicon-time"></i>
          工作计划表
        </a>
        <ul class="nav navbar-nav">
          <li><router-link to="/home">首页</router-link></li>
          <li><router-link to="/time">计划列表</router-link></li>
        </ul>
      </div>
    </div>
  </nav>



</template>

<script>
    export default {
        data() {
            return {}
        },
        computed: {},
        components: {},
        methods: {},
    }
</script>

<style scoped>

</style>
