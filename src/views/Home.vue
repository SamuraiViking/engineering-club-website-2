<template>
  <div class="home">
    <div class="slanted">
      <horizontal-card v-bind:imgPosition="'left'"/>
    </div>
    <div>
      <horizontal-card v-bind:imgPosition="'right'"/>
    </div>

    <div class="slanted">
      <horizontal-card v-bind:imgPosition="'left'"/>
    </div>

    <div>
      <hardware-and-software />
    </div>

    <div class="slanted">
      <meet-the-team />
    </div>

    <div>
      <sponsers />
    </div>


  </div>
</template>

<script>

import SlantedDiv from "@/components/SlantedDiv.vue"
import NonSlantedDiv from "@/components/NonSlantedDiv.vue"
import HorizontalCard from "@/components/HorizontalCard.vue"
import HardwareAndSoftware from "@/components/HardwareAndSoftware.vue"
import MeetTheTeam from "@/components/MeetTheTeam.vue"
import Sponsers from "@/components/Sponsers.vue"

export default {
  name: 'home',
  components: {
    Sponsers,
    HorizontalCard,
    NonSlantedDiv,
    SlantedDiv,
    HardwareAndSoftware,
    MeetTheTeam,
  }
}
</script>


<style>

.home {
  height: 100%;
}

.slanted {
  background: #e74c3c;
  overflow-x: hidden;
  width: 100%;
  clip-path: polygon(0 0, 100% 5%, 100% 95%, 0 100%);
}

</style>