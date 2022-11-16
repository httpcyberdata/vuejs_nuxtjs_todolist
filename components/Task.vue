<template>
  <div :class="`task ${task.done ? 'is-complete' : ''}`">
    <div class="content">
       `{{ task.content }}``
    </div>
    <div class="buttons">
        <button>
           `{{ task.done ? 'Undo' : 'Done' }}`
        </button>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>