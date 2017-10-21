<template>
  <div>
    <navbar/>
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="col-md-3">
            <slidebar></slidebar>
          </div>
          <div class="col-md-9">
            <router-view></router-view>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  import Navbar from '@/components/Navbar'
  import Slidebar from '@/components/Slidebar'

  export default {
    components: {
      Navbar,Slidebar
    }
  }
</script>

<style>

</style>
