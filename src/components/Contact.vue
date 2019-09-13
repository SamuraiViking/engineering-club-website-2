<template>
  <div id="contact">
    <h1 id="contact-header">Contact</h1>
    <div>
      <font-awesome-icon :icon="['fab', 'facebook-square']" size="3x" />
      <font-awesome-icon :icon="['fab', 'youtube']" size="3x" />
      <font-awesome-icon :icon="['fab', 'github']" size="3x" />
    </div>
  </div>
</template>


<script>
  export default {
    name: 'contact'
  }
</script>

<style>

#contact {
  color: white;
  padding: 100px 0 200px 0;
}

</style>