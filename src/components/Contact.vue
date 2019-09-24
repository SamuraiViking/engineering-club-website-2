<template>
  <div id="contact">
    <div id="contact-container">
      <!-- <h1 id="contact-header">Contact</h1> -->
      <h1>stolafEngineers@stolaf.edu</h1>
      <div id="contact-icons">
        <font-awesome-icon :icon="['fab', 'facebook-square']" size="3x" />
        <font-awesome-icon :icon="['fab', 'github']" size="3x" />
        <font-awesome-icon :icon="['fab', 'youtube']" size="3x" />
      </div>
    </div id="contact-container">
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
}

#contact-header {
  margin-bottom: 20px;
}

#contact-container {
  padding: 200px 0 200px 0;
}

font-awesome-icon:hover {
  color: blue !important;
}

#contact-icons {
  width: 200px;
  margin: 0px auto;
  margin-top: 20px;
  justify-content: space-between;
  display: flex;
}

</style>