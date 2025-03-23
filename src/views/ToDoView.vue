<script setup lang="ts">
import ToDoFilters from '@/components/ToDoFilters.vue'
import ToDoSearch from '@/components/ToDoSearch.vue'
import ToDoForm from '@/components/ToDoForm.vue'
import ToDoTaskList from '@/components/ToDoTaskList.vue'
</script>

<template>
  <div class="container">
    <header>
      <h1>ToDo App</h1>
    </header>
    <ToDoForm />
    <ToDoSearch />
    <ToDoFilters />
    <ToDoTaskList />
  </div>
</template>
