<template>
  <section class="todoapp">
    <header class="header">
      <h1>Tarefas</h1>
      <input-task></input-task>
    </header>
  </section>
</template>

<script>
import InputTask from './components/InputTask'

export default {
  name: 'App',
  components: {
    InputTask
  }
}
</script>

<style>

</style>
