<template>
  <div>
    <input class="new-todo"
     @keyup.enter="addTask"
    placeholder="O que precisa ser feito?">
  </div>
</template>

<script>
import { Task } from '../models/Task'

export default {
  name: 'IputTask',
  data () {
    return {}
  },
  methods: {
    addTask ($event) {
      let task = new Task()
      task.completed = false
      task.title = $event.target.value
      console.log(task)
    }
  }
}
</script>

<style>
</style>
