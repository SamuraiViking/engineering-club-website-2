<template>
  <div class="my-horizontal-card">
    <b-card no-body class="overflow-hidden center shadow" style="max-width: 800px;">
      <b-row v-if="imgPosition==='left'"no-gutters>
        <b-col md="6">
          <b-card-img :src="require(`@/assets/${imgSrc}`)" class="rounded-0"></b-card-img>
        </b-col>
        <b-col md="6">
          <b-card-body :title="title">
            <b-card-text class="my-card-text">
              {{ text }}
            </b-card-text>
          </b-card-body>
        </b-col>
      </b-row>
      <b-row v-if="imgPosition==='right'"no-gutters>
        <b-col md="6">
          <b-card-body :title="title">
            <b-card-text class="my-card-text">
              {{ text }}
            </b-card-text>
          </b-card-body>
        </b-col>
        <b-col md="6">
          <b-card-img :src="require(`@/assets/${imgSrc}`)" class="rounded-0"></b-card-img>
        </b-col>
      </b-row>

    </b-card>
  </div>
</template>

<script>
  export default {
    props: ['imgPosition', 'imgSrc', 'title', 'text'],
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


