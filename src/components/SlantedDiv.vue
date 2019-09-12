<template>
  <div :class="`${direction} slanted`">

  </div>
</template>

<script>
  export default {
    name: 'slanted-div',
    props: ['direction'],
    methods: {
      slantDirectionClass(slantDirection) {
        var slantClass = ''
        if(this.slantDirection === 'left') {
          slantClass = 'left-slant'
        } else if (this.slantDirection === 'right') {
          slantClass = 'right-slant'
        }
        return slantClass
      }
    }
  }
</script>


<style>

.slanted {
  height: 900px;
  background: #e74c3c;
  overflow-x: hidden;
  width: 2000px;
  clip-path: polygon(0 0, 100% 15%, 100% 85%, 0 100%);
}

</style>