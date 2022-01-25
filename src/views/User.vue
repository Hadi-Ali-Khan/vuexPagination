<template>
  <!-- <h2 class="user">User {{ $route.params.username }} component</h2> -->
  <h2>User {{ username }} component</h2>
</template>
<script>
export default {
  props: ["username"]
}
</script>
