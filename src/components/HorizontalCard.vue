<template>
  <div class="my-horizontal-card">
    <b-card no-body class="overflow-hidden center shadow" style="max-width: 800px;">
      <b-row v-if="imgPosition==='left'"no-gutters>
        <b-col md="6">
          <b-card-img src="https://picsum.photos/400/400/?image=20" class="rounded-0"></b-card-img>
        </b-col>
        <b-col md="6">
          <b-card-body title="Spacial Awarness">
            <b-card-text class="my-card-text">
t is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using
            </b-card-text>
            <div class="rank">
              <span class="rank-text">4th place</span>
            </div>
          </b-card-body>
        </b-col>
      </b-row>
      <b-row v-if="imgPosition==='right'"no-gutters>
        <b-col md="6">
          <b-card-body title="Spacial Awarness">
            <b-card-text class="my-card-text">
t is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using
            </b-card-text>
            <div class="rank">
              <span class="rank-text">4th place</span>
            </div>
          </b-card-body>
        </b-col>
        <b-col md="6">
          <b-card-img src="https://picsum.photos/400/400/?image=20" class="rounded-0"></b-card-img>
        </b-col>
      </b-row>

    </b-card>
  </div>
</template>

<script>
  export default {
    props: ['imgPosition'],
    name: 'horizontal-card'
  }
</script>

<style>

.rank {
  width: 130px;
  height: 130px;
  background: #e74c3c;
  margin: 0px auto;
  border-radius: 50%;
}

.rank-text {
  font-weight: 900;
  font-size: 20px;
  color: white;
  line-height: 130px;
}

.my-card-text {
  text-align: left;
}

.shadow {
  /*box-shadow: 10px 10px;*/
}

.my-horizontal-card {
  margin: 0px auto;
  padding: 200px 20px;
}

</style>


