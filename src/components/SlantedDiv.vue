<template>
  <div class="slanted">
    <horizontal-card />
  </div>
</template>

<script>
  import HorizontalCard from './HorizontalCard.vue'
  export default {
    name: 'slanted-div',
    components: {
      HorizontalCard,
    }
  }
</script>


<style>

.slanted {
  background: #e74c3c;
  overflow-x: hidden;
  width: 100%;
  clip-path: polygon(0 0, 100% 5%, 100% 95%, 0 100%);
}

</style>