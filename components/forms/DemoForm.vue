<template>
  <div class="form-wrapper" id="form">
    <form>
      <div class="form-group">
        <label for="name">Username:</label>
        <input type="text" v-model="form.username" class="form-control" id="name" >
      </div>
      <div class="form-group">
        <label for="email">Email address:</label>
        <input type="email" v-model="form.email" class="form-control" id="email">
      </div>
      <div class="form-group">
        <label for="pwd">Password:</label>
        <input type="password" v-model="form.password" class="form-control" id="pwd" >
      </div>
      <button type="button" class="btn btn-info btn-lg" data-toggle="modal" data-target="#demoModal" v-on:click="send($event)">Login</button>
    </form>
  </div>
</template>
<script>
export default {

}
</script>
