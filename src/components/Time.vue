<template>
    <div>
      <router-link to="/time/time-add" class="btn btn-primary">创建</router-link>

      <hr>
      <router-view></router-view>
      <ul class="list-group" v-for="list in lists" >
        <li class="list-group-item" >
         <div class="row">
           <div class="col-md-2 text-center">
             <img :src="list.avatar" alt="" class="img-circle img-responsive">{{list.name}}
           </div>
           <div class="col-md-3">
             <div>
               <i class="glyphicon glyphicon-time"></i>{{list.time}}小时

             </div>
             <div class="text-info">
               <i class="glyphicon glyphicon-calender "></i>{{list.date}}
             </div>
           </div>
           <div class="col-md-5">
             <div>
               {{list.comment}}
             </div>
           </div>
           <div class="col-md-2">
             <button class="btn btn-danger">&times;</button>
           </div>
         </div>
        </li>
      </ul>
    </div>
</template>

<script>
  export default {
    data(){
      return {
        lists:[
          {
        avatar:'https://ss2.bdstatic.com/70cFvnSh_Q1YnxGkpoWK1HF6hhy/it/u=634098145,264198475&fm=27&gp=0.jpg',
          name:'jw',
          date:'2017年',
          times:2,
          comment:'今天回家吃饭',

      }
        ]

      }
    },
    computed: {},
    components: {},
    methods: {},
  }

</script>

<style scoped>
div{
  line-height: 30px;
}
</style>

