<template>
  <div id="landing-page">
    <div id="top-section">
      <div id="top-section-container">
        <h1 type="info" id="top-section-title">Stolaf & Carlton Engineering Club</h1>
        <div id="top-section-btns">
          <div id="join-now-container">
            <b-button variant="light" size="lg" block>Join Now</b-button>
          </div>
          <div id="see-more-container">
            <b-button variant="light" class="see-more-btn" size="lg" block>
              <a id="see-more-link" href="#projects" v-smooth-scroll>See More</a>
            </b-button>
          </div>
        </div>
      </div>
      <div id="image-container">
        <img id="drone-img" src="https://www.jawbone.org/images/articles/dji_drone.png" />
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



#see-more-link {
  color:#212529;
}

#see-more-link:hover {
  text-decoration: none;
}


#drone-img {
  width: 100%;
  height: auto;
  max-width: 600px;
}

#top-section-title {
  /* max-width: 300px; */
  margin-bottom: 30px;
}


#top-section-container {
  color: white;
  max-width: 1000px;
  margin: 0px auto;
  text-align: center;
  /* color: white; */
}


#top-section {
  padding: 0 50px;
}

#top-section-btns {
  margin-top: 50px;
  display: flex;
  justify-content: center;
}

#join-now-container {
  width: 250px;
  margin-right: 50px;
}

#see-more-container {
  width: 250px;
}

#landing-page {
  padding-top: 200px;
  position: relative;
  background-color: #e74c3c;
  height: 110%;
  justify-content: center;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  clip-path: polygon(0 0, 100% 0%, 100% 95%, 0 100%);
}

</style>