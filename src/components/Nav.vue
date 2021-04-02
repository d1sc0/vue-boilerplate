<template>
  <nav id="nav">
   <div class="container mt-5">
      <router-link :to="{ name: 'Home' }" class="is-size-5 has-text-weight-semibold">Home</router-link> 
    </div>
</nav>
</template>

<script>
export default {
  name: 'Nav'
}
</script>
