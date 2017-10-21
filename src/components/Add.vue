<template>
    <div>
      <form>
        <div class="form-group">
          <div class="row">
            <div class="col-md-6">
              <label for="date" class="control-label">日期</label>
              <input type="date"  class="form-control" id="date">
            </div>
            <div class="col-md-6">
              <label for="time" class="control-label">时间</label>
              <input type="number"  class="form-control" id="time">
            </div>
          </div>
        </div>
        <div class="form-group">
          <textarea class="form-control" palceholder="请输入内容" name="" id="" cols="30" rows="5"></textarea>
        </div>
        <div class="form-group">
          <button class="btn btn-success">添加计划</button>
          <button class="btn btn-danger">取消</button>
        </div>
      </form>

    </div>
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
