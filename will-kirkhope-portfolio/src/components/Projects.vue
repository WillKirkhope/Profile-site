<template lang="html">
  <div class="Proj-container">
    <div class="backgroundImg2">

    </div>
    <h1>Projects</h1>
    <div class="project">
      <a href="https://github.com/WillKirkhope/Capstone-FrontEnd">Fireteam Finder</a>
      <p>Fireteam Finder is a full stack web application that serves as a social space for gamers to connect, link up and play their favorite games. Users can create posts for other players to see as well as chat with other players in the chat room. Users can also create a viewable profile the describes how they play as well as their favorite games, and include a brag video so other users can see a visual demonstration of skill.</p>
      <p>Tech Used: HTML, CSS, JavaScript, Bootstrap, Firebase, VueJS, Heroku, PostgreSQL, Knex, Express, Git/Github, Socket.io</p>
      <img src="../assets/FireteamFinder.png" alt="" class="ProjImg">
    </div>
    <div class="project">
      <a href="https://github.com/WillKirkhope/Borough-FrontEnd/tree/master/borough-fe">The Borough</a>
      <p>The Borough was an app created initially as a student project with a timeline of four days and the challenge of learning a new framework on top of that. The app is a meetup app geared towards getting community service events started and bringing knowledge about them to more people.</p>
      <p>Tech Used: HTML, CSS, JavaScript, Bootstrap, Firebase, VueJS, Heroku, PostgreSQL, Knex, Express, Git/Github, GoogleMaps</p>
      <img src="../assets/TheBorough.png" alt="" class="ProjImg">
    </div>
    <div class="project">
      <a href="https://github.com/WillKirkhope/Dormistore-client">Dormistorë</a>
      <p>Dormistore is a simple CRUD app designed to be an Admin side of a dorm/apartment storefront site, the admin has access to all the products, the can add more, and edit the amount of product they have, as well and delete sold out items. Future implementations coming soon!</p>
      <p>Tech Used: CSS, HTML, JavaScript, React, Knex, Heroku, PostgreSQL, Firebase, Express</p>
      <img src="../assets/dormistore.png" alt="" class="ProjImg">
    </div>
    <div class="project">
      <a href="https://github.com/WillKirkhope/Portfolio-site">This Site</a>
      <p>A clean simple portfolio site</p>
      <p>Tech Used: VueJS, Bootstrap, CSS, HTML, JavaScript, Firebase</p>
      <img src="../assets/personal.png" alt="" class="ProjImg">
    </div>
    <div class="project">
      <a href="https://pokemon-selector-46ace.firebaseapp.com/">Pokemon Team Selector</a>
      <p>Ever wanted to see what your ideal Pokémon Team is, or compare it to a friends, or do you know a Pokémon name but don't know how it looks? Well Pokémon Team Selector is for you! This is a fun little app to help you visualize your very own Pokémon Team!</p>
      <p>Tech Used: JavaScript, CSS, HTML, Firebase</p>
      <img src="../assets/pokemon.png" alt="" class="ProjImg">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Projects'
}
</script>

<style>

.backgroundImg2 {
    background-image: url("../assets/Code.png");
    height: 38vw;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

a {
  font-size: 24px;
  color: #2c3e50;
}

.ProjImg {
  height: 15vw;
  width: 20vw;
}

.project{
  padding-left: 5vw;
  padding-right: 5vw;
}

</style>
