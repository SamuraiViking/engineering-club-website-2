<template>
  <div id="meet-the-team">
    <h1 id="header">Meet the Team</h1>
    <div id="team-container">
      <div v-for="person in people">
        <b-card
          img-src="https://picsum.photos/400/400/?image=20"
          :title="person.name"
          style="width: 200px; height: 400px; margin: 20px;"
        >
          <b-card-text>
            {{ person.description }}
          </b-card-text>
        </b-card>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "meet-the-team",
    data() {
      return {
        people: [
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
          {name: "Kevin", description: "cool"},
        ]
      }
    }
  }
</script>

<style>

#header {
  color: white;
  margin-bottom: 50px;
}
  
#meet-the-team {
  padding: 200px 0px;
}

#team-container {
  display: flex;
  overflow-x: scroll;
  margin: 0 50px;
}

</style>