<template>
  <div class="my-horizontal-card">
    <div class="center" no-body style="max-width: 800px;">
      <b-row>
        <b-col md="6">
          <div class="red-box">
            <h1 class="label">Hardware Team</h1>
            <p class="red-box-description">
              Computer engineering is a branch of engineering that integrates several fields of computer science and electronic engineering required to develop computer hardware and software. Computer engineers usually have training in electronic engineering (or electrical engineering), software design, and hardware-software integration instead of only software engineering or electronic engineering.
            </p>
            <div class="more-btn">
              <router-link to="/hardware">
                <span class="more-btn-txt">Read More</span>
              </router-link>
            </div>
          </div>
        </b-col>
        <b-col md="6">
          <div class="red-box">
            <h1 class="label">Software Team</h1>
            <p class="red-box-description">
              Computer software, or simply software, is a collection of data or computer instructions that tell the computer how to work. This is in contrast to physical hardware, from which the system is built and actually performs the work. In computer science and software engineering, computer software is all information processed by computer systems, programs and data.
            </p>
            <div class="more-btn">
              <router-link to="/software">
                <span class="more-btn-txt">Read More</span>
              </router-link>
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

.red-box-description {
  color: white;
  height: 0px;
  overflow: hidden;
  transition: 0.3s ease;
}

.red-box:hover .red-box-description {
  height: 100px;
}

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
  text-decoration: none;
  color: #e74c3c;
  line-height: 45px;
  transition: ease 0.3s;
  font-weight: 400;
}

.more-btn-txt:hover {
  text-decoration: none !important;
}

.red-box {
  margin-bottom: 50px;
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
  border: 2px solid white;
  margin: 25px auto 0px auto;
  width: 100px;
  height: 100px;
  border-radius: 50%;
}

.red-box:hover .more-btn-txt {
  color: white;
  line-height: 95px;
  font-weight: 900;
}

.more-btn:hover {
  background: white;
}

.more-btn:hover .more-btn-txt {
  color: red;
  text-decoration: none !important;
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