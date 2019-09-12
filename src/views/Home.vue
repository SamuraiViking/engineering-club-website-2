<template>
  <div class="home">
<!--     <horizontal-card />
    <horizontal-card />
    <horizontal-card />
    <horizontal-card />
    <horizontal-card /> -->
    <slanted-div />
    <non-slanted-div />
    <slanted-div />
    <non-slanted-div />
    <slanted-div />
    <non-slanted-div />
  </div>
</template>

<script>

import SlantedDiv from "@/components/SlantedDiv.vue"
import NonSlantedDiv from "@/components/NonSlantedDiv.vue"
import HorizontalCard from "@/components/HorizontalCard.vue"

export default {
  name: 'home',
  components: {
    HorizontalCard,
    NonSlantedDiv,
    SlantedDiv,
  }
}
</script>


<style>

.home {
  height: 100%;
}

</style>