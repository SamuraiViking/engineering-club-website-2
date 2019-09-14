<template>
  <div id="meet-the-team">
    <h1 id="header">The Engineers</h1>
    <div id="team-container">
      <div v-for="person in people">
        <b-card
          :img-src="person.img"
          :title="person.name"
          style="width: 200px; height: 430px; margin: 20px;"
        >
          <b-card-text class="myText">
            <p>
              {{ person.description }}
            </p>
            <p>
              {{ person.year }}
            </p>
            <p>
              {{ person.majior }}
            </p>
            <p>
              {{ person.team }}
            </p>
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
           name: "Sally", 
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=mannin4&v=E3B0C44&fullsize",
           year: '2020',
           majior: 'Physics',
           team: 'Hardware',
           quote: ''
          },
          {
           name: "Marry", 
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=bourqu1&v=20F2DC5&fullsize",
           year: '2020',
           majior: 'CS',
           team: 'Software',
           quote: ''
          },
          {
           name: "George", 
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=arbana1&v=E3B0C44&fullsize",
           year: '2019',
           majior: 'Math',
           team: 'Hardware',
           quote: ''
          },
          {
           name: "Allen", 
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=allen10&v=E3B0C44&fullsize",
           year: '2020',
           majior: 'CS',
           team: 'Software',
           quote: ''
          },
          {
           name: "Kevin", 
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=nelson67&v=E3B0C44&fullsize",
           year: '2019',
           majior: 'CS',
           team: 'Software',
           quote: ''
          },
          {
           name: "Matt", 
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=bongar2&v=E3B0C44&fullsize",
           year: '2019',
           majior: 'Physics',
           team: 'Hardware',
           quote: ''
          },
          {
           name: "Annie", 
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=bley1&v=E3B0C44&fullsize",
           year: '2023',
           majior: 'English',
           team: 'Software',
           quote: ''
          },
          {
           name: "Reina", 
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=collin15&v=E3B0C44&fullsize",
           year: '2022',
           majior: 'History',
           team: 'Software',
           quote: ''
          },
          {
           name: "Jason", 
           img: "https://www.stolaf.edu/stofaces/face.cfm?username=tan4&v=C3A536A&fullsize",
           year: '2018',
           majior: 'Music',
           team: 'Hardware',
           quote: ''
          }
        ]
      }
    }
  }
</script>

<style>

.myText {
  text-align: left;
  line-height: 10px;
}

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