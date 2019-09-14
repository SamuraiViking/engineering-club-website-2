<template>
  <div id="meet-the-team">
    <h1 id="header">The Engineers</h1>
    <div id="team-container">
      <div v-for="person in people">
        <b-card
          :img-src="person.img"
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
          {
           name: "Kevin", 
           description: "cool",
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=nelson67&v=E3B0C44&fullsize"
          },
          {
           name: "Sally", 
           description: "cool",
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=mannin4&v=E3B0C44&fullsize",
          },
          {
           name: "Marry", 
           description: "cool",
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=bourqu1&v=20F2DC5&fullsize"
          },
          {
           name: "George", 
           description: "cool",
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=arbana1&v=E3B0C44&fullsize"
          },
          {
           name: "Allen", 
           description: "cool",
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=allen10&v=E3B0C44&fullsize"
          },
          {
           name: "Matt", 
           description: "cool",
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=bongar2&v=E3B0C44&fullsize"
          },
          {
           name: "Annie", 
           description: "cool",
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=bley1&v=E3B0C44&fullsize",
          },
          {
           name: "Reina", 
           description: "cool",
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=collin15&v=E3B0C44&fullsize"
          },
          {
           name: "Jason", 
           description: "cool",
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=tan4&v=C3A536A&fullsize"
          }
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