<template>
  <div id="app">
      <div class="container">
          <div class="row">
              <div class="col-md-6">
                <create-todo></create-todo>
              </div>
               <div class="col-md-6">
                <list-todo></list-todo>
              </div>   
          </div>
      </div>
  </div>
</template>

<script>
import CreateTodo from './CreateTodo.vue';
import ListTodo from './ListTodo.vue';

export default {
    name: 'app',
    data(){
        return {}
    }, 
    components : {CreateTodo, ListTodo}
}
</script>


<style>
  .fade-enter-active,
  .fade-leave-active {
    transition: opacity .5s
  }
  .fade-enter,
  .fade-leave-active {
    opacity: 0
  }
</style>