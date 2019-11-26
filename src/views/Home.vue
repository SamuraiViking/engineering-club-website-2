<template>
  <div class="home">
    <landing-page />
    <div>
      <about />
    </div>
    <div class="slanted">
      <horizontal-card v-bind:imgPosition="'left'"
                       v-bind:imgSrc="'droneWorking.png'"
                       v-bind:title="'Laser Tag'"
                       v-bind:text="`${text1}`"/>
                       />
    </div>
    <div>
      <horizontal-card v-bind:imgPosition="'right'"
                       v-bind:imgSrc="'droneWorking2.png'"
                       v-bind:title="'Racing'"
                       v-bind:text="`${text2}`"/>
    </div>

    <div class="slanted">
      <horizontal-card v-bind:imgPosition="'left'"
                       v-bind:imgSrc="'droneWorking3.png'"
                       v-bind:title="'Photography'"
                       v-bind:text="`${text3}`"/>
                       />
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
  },

  data() {
      return {
        text1: "Create drones that shoot other drones with laser beams! You get points for shooting down other drones and staying alive in the arena.",
        text2: "FPV drone racing (where FPV stands for first-person view or first person video) is a sport type where participants control \"drones\", equipped with cameras while wearing head-mounted displays showing the live stream camera feed from the drones.",
        text3: "Aerial photography (or airborne imagery) is the taking of photographs from an aircraft or other flying object. Platforms for aerial photography include fixed-wing aircraft, helicopters, unmanned aerial vehicles (UAVs or \"drones\"), balloons, blimps and dirigibles, rockets, pigeons, kites, parachutes, stand-alone telescoping and vehicle-mounted poles"
    }
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