<template>
  <div id="landing-page">
    <div class="container">
      <div>
        <h1>Stolaf and Carlton Engineers</h1>
        <div id="action-btns">
          <b-button variant="light" size="lg">Join Now</b-button>
          <b-button variant="light" size="lg">See More</b-button>
        </div>
      </div>
      <div id="image-container">
        <img src="https://www.jawbone.org/images/articles/dji_drone.png" />
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'landing-page'
  }
</script>

<style>

#landing-page .container {
  width: 100%;
  display: flex;
}

#landing-page h1 {
  margin-bottom: 50px;
}

#image-container {
  /* background: blue; */
}

#action-btns {
  display: flex;
  max-width: 300px;
  margin: 0px auto;
  /* background: blue; */
  justify-content: space-between;
}



#landing-page {
  color: white;
  padding-top: 100px;
  background-color: #e74c3c;
  height: 110%;
  clip-path: polygon(0 0, 100% 0%, 100% 95%, 0 100%);
}

</style>