<template>
  <div class="about">
    <h1>Vue Todos</h1>
    <p>Vue Todos is a CRUD Todo tracking application created for a Vue 3 Crash Course by John Komarnicki</p>
    <p>Track you daily task's using this todo tracker cith abilities to save, complete, edit & delete todos</p>
    <p>Feel free to add on to this application with functionalities such as the ability to drag and reorder todos, animate creation/deletion of todos or even create this into a full stack application with the ability to hace different lists of different days of tracking todos8</p>
  </div>
</template>

<style>
.about {
    max-width: 800px;
    margin: 0 auto;
    padding: 25px 16px;
  }

.about h1 {
  margin-bottom: 20px;
}

.about > p + p {
  margin-top: 10px;
}
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
  }
}
</style>
