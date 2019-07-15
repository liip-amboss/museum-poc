<template>
  <div class="container">
    <div>
      <img src="~/assets/images/smoke.png">
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

body {
  background-color: #c7c7c7;
}

</style>
