<template>
  <div class="about">
    <h1>Vue Todos</h1>

    <p id="words">
      Vue Todos is a CRUD Todo tracking application created by Charles Ifeanyi.<br><br>
      Track your daily task's using this todo tracker with abilities to save, complete, edit & delete todos.<br><br>
      Feel free to add on to this application with functionalities such as the ability to drag and reorder 
      todos, animate creation/deletion of todos or even create this into a full stack application with 
      the ability to have different lists for different days of tracking todos!
    </p>
  </div>
</template>

<style>

  .about {
    min-height: 100vh;
    display: block;
    margin: 20px 20%;
  }

  .about h1 {
    margin-bottom: 20px; 
  }

  .about #words {
    line-height: 25px;
    font-weight: 500;
  }

</style>
