<template>
  <div id="app">
    <todo-header></todo-header>
    <todo-input></todo-input>
    <todo-list></todo-list>
    <todo-footer></todo-footer>
  </div>
</template>

<script>
import TodoHeader from "./components/TodoHeader.vue"
import TodoInput from "./components/TodoInput.vue"
import TodoList from "./components/TodoList.vue"
import TodoFooter from "./components/TodoFooter.vue"

// var my_cmp = {
//   template : '<div>my component</div>'
// };

// new Vue({
//   el: '',
//   components: {
//     'my-cmp' : my_cmp
//   }
// })

export default {
  components :{
    'TodoHeader':TodoHeader,
    'TodoInput': TodoInput,
    'TodoList': TodoList,
    'TodoFooter': TodoFooter
  }

}
</script>

<style>

</style>