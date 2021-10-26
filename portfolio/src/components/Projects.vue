<template>
  <div class="PflexCon">
    <h3>Projects</h3>
    <div>
      <h4>CommBase <a href="https://commbase.herokuapp.com/" target="_blank" rel="noopener noreferrer">Site Link</a></h4>
      <div>CommBase is a communication platform inspired by discord and slack with user created and managed servers. CommBase is a full-stack application built with MongoDB, Express, Vue, and Node. this application also includes full user authentication built into our RESTful API.</div>
    </div>
    <div>
      <h4>DVLPR <a href="https://dvlpr-app.herokuapp.com/" target="_blank" rel="noopener noreferrer">Site Link</a></h4>
      <div>DVLPR is a social platform for all software developers to come together and network on. This aims to solve an issue with many developers throughout the world using many different platforms to connect. DVLPR is built using PERN Stack (PostgresSQL, ExpressJs, ReactJs, and Node.js) and has full user and password authentication. The back-end has a RESTful api.</div>
    </div>
    <div>
      <h4>Eve HyperNet Manager <a href="https://secure-stream-53418.herokuapp.com/" target="_blank" rel="noopener noreferrer">Site Link</a></h4>
      <div>as we all know internet spaceships is very serious business, and with serious business come serious spread sheets. I made this application to make one part of your internet space job much easier.
        <br>
      this application tracks Jita market data, calculates and tracks how profitable a ship is when raffled off on the HyperNet with a 50% buy in. as well as give relivent related values.
        <br>
      this application was made with MongoDB, Express, React, and Node.
      </div>
      <div>
      <h4>Zerg Rush <a href="https://zerg_rush.surge.sh/" target="_blank" rel="noopener noreferrer">Site Link</a></h4>
      <div>this is a grid based defence game build only using HTML, CSS, and Javascript. the goal of the game is to hold out for as long as possible agianst the swarm. how many can you take down before succumb to the shear numbers of the hive mind.</div>
    </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Projects"
}
</script>

<style scoped>
.PflexCon {
  margin: 20px;
  display: flex;
  flex-direction: column;
  background-color: #565656cb;
  padding: 20px;
  border-radius: 50px;
}
</style>