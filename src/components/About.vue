<template>
  <div id="about">
    <h1>International Aerial Robotics Competition</h1>
    <img src="https://i.ytimg.com/vi/2w08D9MoOMk/maxresdefault.jpg">
    <p>
It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).
    </p>
  </div>
</template>

<script>
export default {
  name: 'about'
}
</script>

<style>

.ranks {
  display: flex;
  /* background: blue; */
  justify-content: space-between;
}

.ranks .rank {
  color: white;
  font-weight: 900;
  font-size: 35px;
}

#about {
  max-width: 800px;
  margin: 0px auto;
  padding: 100px 20px;
}

#about h1 {
  margin-bottom: 30px;
}

#about img {
  width: 100%;
  height: auto;
  margin-bottom: 30px;
}


</style>