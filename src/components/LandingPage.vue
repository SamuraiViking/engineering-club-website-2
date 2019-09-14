<template>
  <div id="landing-page">
    <div class="container">
      <div class="content">
        <h1>Stolaf and Carlton Engineers</h1>
        <div id="action-btns">
          <b-button id="join" variant="light" size="lg">
            <a href="#contact" v-smooth-scroll>Join Now</a>
          </b-button>
          <b-button id="more" variant="outline-light" size="lg">
            <a href="#about" v-smooth-scroll>See More</a>
          </b-button>
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
  text-align: left;
}

#landing-page h1 {
  margin-bottom: 50px;
}

#action-btns {
  display: flex;
}

#action-btns #join {
  width: 200px;
  margin-right: 30px;
}

@media only screen and (max-width: 800px) {
  #landing-page .container {
    display: block;
  }
}

#image-container img {
  width: 100%;
  height: auto;
}

#more a {
  color: white;
}

#join a {
  color: black;
}

#join:hover a {
  text-decoration: none;
}

#more:hover a {
  color: black;
  text-decoration: none;
}





#landing-page {
  color: white;
  padding-top: 100px;
  background-color: #e74c3c;
  height: 110%;
  clip-path: polygon(0 0, 100% 0%, 100% 95%, 0 100%);
}

</style>