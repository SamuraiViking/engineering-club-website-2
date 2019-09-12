<template>
  <div class="home">
    <div class="slant-top"></div>
    <slanted-div />
    <div class="non-slanted"></div>
    <slanted-div />
    <div class="non-slanted"></div>
    <slanted-div />
    <div class="non-slanted"></div>
    <slanted-div />
    <div class="non-slanted"></div>
    <slanted-div />
    <div class="non-slanted"></div>
    <slanted-div />
    <div class="non-slanted"></div>
    <slanted-div />
    <div class="non-slanted"></div>
    <slanted-div />
    <div class="non-slanted"></div>
    <slanted-div />
    <div class="non-slanted"></div>
    <slanted-div />

  </div>
</template>

<script>

import SlantedDiv from "@/components/SlantedDiv.vue"

export default {
  name: 'home',
  components: {
    SlantedDiv
  }
}
</script>


<style>

.home {
  height: 100%;
}

.hero-image__figure img {
  -webkit-clip-path: polygon(0 0, 100% 0, 100% 96%, 0 100%);
  clip-path: polygon(0 0, 100% 0, 100% 96%, 0 100%);
}

.non-slanted {
  /*background: blue;*/
  height: 700px;
}

.slant-top {

}

</style>