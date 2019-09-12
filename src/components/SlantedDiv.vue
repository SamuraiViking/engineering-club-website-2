<template>
  <div class="slanted">
  </div>
</template>

<script>
  export default {
    name: 'slanted-div'
  }
</script>


<style>

.slanted {
  height: 120%;
  background: #e74c3c;
  overflow-x: hidden;
  width: 100%;
  clip-path: polygon(0 0, 100% 5%, 100% 95%, 0 100%);
}

</style>