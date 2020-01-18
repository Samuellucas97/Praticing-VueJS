<template>
  <v-container>
    <v-row no-gutters>
      <v-col cols="12">
        <v-row  justify="center">
          <div>
            <v-card
              class="mx-auto rounded-card"
              max-width="200"
            >
              <v-img
                class="white--text align-end"
                src="../assets/samuel.png"
              >
              </v-img>
            </v-card>
          </div>
        </v-row>
      <v-col cols="12">
        <v-row align="start" justify="center">
          <div>
            <h1>Samuel Lucas</h1>
            <h3>Android and Full-stack development</h3>
          </div>
        </v-row>
      </v-col>
      <hr> 
      </v-col>
      <v-spacer></v-spacer>
      <v-col cols="12">
        <v-row align="start" justify="center">
          <div>
            <a href="https://github.com/Samuellucas97" target="_blank"><i class="fab fa-github-square"></i></a>
            <a href="http://www.linkedin.com/in/samuel-lucas-a0802a154" target="_blank"><i class="fab fa-linkedin" ></i></a>
            <a href="https://dev.to/samuellucas97" target="_blank"><i class="fab fa-dev"></i></a>
            <a href="https://www.researchgate.net/profile/Samuel_Ferino" target="_blank"><i class="fab fa-researchgate"></i></a>
            <a href="https://stackoverflow.com/story/samuellucas97" target="_blank"><i class="fab fa-stack-overflow"></i></a>
          </div>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'About',
  mounted() {
    let fontawesome = document.createElement('script')
    fontawesome.setAttribute('src', 'https://kit.fontawesome.com/a076d05399.js')
    document.head.appendChild(fontawesome)
  }
};
</script>

<style scoped>

i.fab {
  font-size:50px;
  padding-right:20px;
  color:white;
}
h1,h3 {
	text-align:center;
	color:white;
}
h1 {
  margin-top: 40px;
	font-size: 55px;
}
h3 {
  margin-top: -20px;
	font-size: 30px;
}

hr {
margin: 10px 320px 20px;
}

.rounded-card{
margin: 20px 0px 0px;
}
</style>



