<template>
  <div id="landing-page">
    <div id="landing-content">
      <h1 id="landing-content-title">Stolaf and Carlton Engineering Team</h1>
      <div id="landing-btns">
        <b-button size="lg" variant="primary" id="join-btn">Join Now</b-button>
        <b-button size="lg" variant="primary" id="more-btn">See More</b-button>
      </div>
    </div>
    <!-- <img src="../assets/drone.jpg"/> -->
  </div>
</template>

<script>
export default {
  name: 'landing-page',
}
</script>

<style>

#landing-content-title {
  max-width: 300px;
  font-size: 40px;
  margin-bottom: 60px;
}

#landing-content {
  margin: 0px auto;
  padding: 20px;
  max-width: 600px;
  text-align: left;
}

#join-btn {
  width: 300px;
}

#more-btn {
  width: 200px;
}

#landing-page {
  /* background: blue; */
  height: 100%;
  /* background-image: url("../assets/drone.jpg") center no-repeat cover; */
  background: url("../assets/drone.jpg") no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
</style>