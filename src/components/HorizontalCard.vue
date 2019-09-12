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
  <div class="my-horizontal-card">
    <b-card no-body class="overflow-hidden center" style="max-width: 800px;">
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

.center {
  margin: 0px auto;
}

.my-horizontal-card {
  padding: 200px 20px;
}

</style>


