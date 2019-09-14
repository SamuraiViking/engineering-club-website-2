<template>
  <div class="home">
    <landing-page />
    <div>
      <about />
    </div>
    <div class="slanted">
      <horizontal-card v-bind:imgPosition="'left'"
                       v-bind:imgSrc="'droneWorking.png'"
                       v-bind:title="'Laser Tag'"/>
    </div>
    <div>
      <horizontal-card v-bind:imgPosition="'right'"
                       v-bind:imgSrc="'https://st3.depositphotos.com/1010683/15722/i/1600/depositphotos_157228044-stock-photo-asian-woman-controlling-drone.jpg'"
                       v-bind:title="'Racing'"/>
    </div>

    <div class="slanted">
      <horizontal-card v-bind:imgPosition="'left'"
                       v-bind:imgSrc="'droneWorking.png'"
                       v-bind:title="'Camera'"/>
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

    <div class="slanted-top">
      <contact />
    </div>

  </div>
</template>

<script>

import About from "@/components/About.vue"
import SlantedDiv from "@/components/SlantedDiv.vue"
import NonSlantedDiv from "@/components/NonSlantedDiv.vue"
import HorizontalCard from "@/components/HorizontalCard.vue"
import HardwareAndSoftware from "@/components/HardwareAndSoftware.vue"
import MeetTheTeam from "@/components/MeetTheTeam.vue"
import Sponsers from "@/components/Sponsers.vue"
import Contact from "@/components/Contact.vue"
import LandingPage from "@/components/LandingPage.vue"

export default {
  name: 'home',
  components: {
    About,
    LandingPage,
    Contact,
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

.slanted-top {
  background: #e74c3c;
  clip-path: polygon(0 0, 100% 5%, 100% 100%, 0 100%);
}

.slanted {
  background: #e74c3c;
  overflow-x: hidden;
  width: 100%;
  clip-path: polygon(0 0, 100% 5%, 100% 95%, 0 100%);
}

</style>