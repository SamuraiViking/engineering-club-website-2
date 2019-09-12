<template>
  <div class="my-horizontal-card">
    <div class="center" no-body style="max-width: 800px;">
      <b-row>
        <b-col md="6">
          <div class="red-box">
            <h1 class="label">Hardware</h1>
            <div class="more-btn">
              <span class="more-btn-txt">Read More</span>
            </div>
          </div>
        </b-col>
        <b-col md="6">
          <div class="red-box">
            <h1 class="label">Software</h1>
            <div class="more-btn">
              <span class="more-btn-txt">Read More</span>
            </div>
          </div>
        </b-col>
      </b-row>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'hardware-and-software'
  }
</script>

<style>

.image-container {
  width: 40%;
}

.image {
  height: 100%;
  width: 100%;
}

.more-btn {
  color: #e74c3c;
  width: 120px;
  height: 50px;
  border-radius: 5px;
  border: 2px solid #e74c3c;
  margin: 50px auto 0px auto;
  transition: ease 0.3s;
}

.more-btn-txt {
  line-height: 45px;
  transition: ease 0.3s;
  font-weight: 400;
}

.red-box {
  width: 100%;
  height: 500px;
  border: 5px solid #e74c3c;
  transition: ease 0.3s;
  border-radius: 10px;
}

.red-box:hover {
  background: #e74c3c;
}

.red-box:hover .more-btn {
  color: white;
  border: 2px solid white;
  margin: 25px auto 0px auto;
  width: 100px;
  height: 100px;
  border-radius: 50%;
}

.red-box:hover .more-btn-txt {
  line-height: 95px;
  font-weight: 900;
}

.more-btn:hover {
  background: white;
  color: red !important;
}

.more-btn:hover .more-btn-txt {

}

.label {
  margin-top: 50px;
  color: black;
  font-size: 60px;
  -webkit-text-fill-color: white;
  -webkit-text-stroke-width: 2px;
  -webkit-text-stroke-color: #e74c3c;
}

#software {
  width: 100%;
  height: 500px;
  border: 5px solid #e74c3c;
  border-radius: 10px;
}

</style>