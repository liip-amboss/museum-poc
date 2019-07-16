<template>
  <div>
    <div class="container">
      <div>
        <img src="~/assets/images/amboss.png"> </div>
    </div>
    <div>
      <nav>
        <router-link to="/info">Info</router-link>
      </nav>
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
  display: flex;
  justify-content: center;
  text-align: center;
}

nav {
  padding: 2rem;
}
</style>
