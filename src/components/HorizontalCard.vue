<template>
<!--   <div class="horizontal-card">
    <div class="container">
      <div class="img">
        <img src="https://i2.wp.com/wp.stolaf.edu/wp-content/uploads/2017/09/DSC0346.jpg?resize=600%2C350&ssl=1">
      </div>
      <div class="text">
        <p>
It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page
        </p>
      </div>
    </div>
  </div> -->
  <div>
    <b-card no-body class="overflow-hidden" style="max-width: 540px;">
      <b-row no-gutters>
        <b-col md="6">
          <b-card-img src="https://picsum.photos/400/400/?image=20" class="rounded-0"></b-card-img>
        </b-col>
        <b-col md="6">
          <b-card-body title="Horizontal Card">
            <b-card-text>
              This is a wider card with supporting text as a natural lead-in to additional content.
              This content is a little bit longer.
            </b-card-text>
          </b-card-body>
        </b-col>
      </b-row>
    </b-card>
  </div>
</template>

<script>
  export default {
    name: 'horizontal-card'
  }
</script>

<style>

.horizontal-card {
  padding: 200px 20px;
}

.horizontal-card .container {
  background: blue;
  display: flex;
  max-width: 1000px;
  margin: auto;
  border-radius: 20px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  background: white;
  overflow: hidden;
}

.horizontal-card .container .img {
  width: 60%;
}

.horizontal-card .container .img img {
  width: 100%;
  height: 100%;
}

.horizontal-card .container .text {
  padding: 20px;
  width: 50%;
}

@media only screen and (max-width: 800px) {
  .horizontal-card .container {
    display: block;
  }

  .horizontal-card .container .img {
    width: 100%;
  }
}

</style>


