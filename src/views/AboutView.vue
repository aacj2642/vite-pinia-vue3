<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<script>
import AOS from "aos"

export default {
  mounted(){
    AOS.init()
  }
}
</script>
<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
