<!-- basic single-file component -->

<template>
  <h2 class="red">{{msg}}</h2>
</template>

<script>
module.exports = {
  // test data
  data () {
    return {
      msg: 'Hello'
    }
  }
}
</script>

<style>
comp-a h2 {
  color: #f00;
}
</style>
