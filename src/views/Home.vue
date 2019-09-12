<template>
  <div class="home">
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

export default {
  name: 'home',
  components: {
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