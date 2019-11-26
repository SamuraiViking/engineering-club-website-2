<template>
  <div id="about">
    <h1>International Aerial Robotics Competition</h1>
    <img src="https://i.ytimg.com/vi/2w08D9MoOMk/maxresdefault.jpg">
    <p>
    The Association for Unmanned Vehicle Systems International Foundation's International Aerial Robotics Competition is the longest running collegiate aerial robotics challenge in the world, having celebrated its quarter century anniversary in 2016. The primary purpose of the IARC is to move the state-of-the-art in aerial robotics forward through the creation of significant and useful mission challenges that are considered 'impossible' at the time that they are proposed.
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