<template>
  <div class="notes">

    <div class="card has-background-success-dark p-4 mb-5">
      <div class="field">
        <div class="control">
          <textarea class="textarea" placeholder="Add a new note"></textarea>
        </div>
      </div>

      <div class="field is-grouped is-grouped-right">
        <div class="control">
          <button class="button is-link has-background-success">Add new note</button>
        </div>
      </div>
    </div>    

    <div v-for="i in 3" class="card mb-4">
      <div class="card-content">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Expedita, impedit rerum voluptas quisquam delectus nemo harum officiis inventore, enim libero veniam doloribus voluptatum eligendi aliquid laboriosam, dolores nam deleniti accusantium.
      </div>
      <footer class="card-footer">
        <a href="#" class="card-footer-item">Edit</a>
        <a href="#" class="card-footer-item">Delete</a>
      </footer>
    </div>
  </div>
</template>