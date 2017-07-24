<template>
  <div class="hello">
    <nav class="navbar fixed-top navbar-toggleable-md navbar-light">
      <a class="navbar-brand" href="#">About</a>
      <a class="navbar-brand" href="#">Projects</a>
      <a class="navbar-brand" href="#">Education</a>
      <a class="navbar-brand" href="#">Skills</a>
      <a class="navbar-brand" href="#">Contact</a>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
        </div>
      </div>
    </nav>
    <div class="jumbotron">
      <h1 class="display-3">My Work!</h1>
    </div>
    <div class="row">
      <div class="card-deck">
        <div class="card">
          <img class="card-img-top" src="" alt="Card image cap">
          <div class="card-block">
            <h4 class="card-title">Pintrest Remake</h4>
            <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
            <p class="card-text">
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </p>
          </div>
        </div>
        <div class="card">
          <img class="card-img-top" src="" alt="Card image cap">
          <div class="card-block">
            <h4 class="card-title">Chore Wars</h4>
            <a href="https://chorewars.herokuapp.com/#/" class="btn btn-primary" target="_blank">Live Demo</a>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="card-deck">
        <div class="card">
          <img class="card-img-top" src="" alt="Card image cap">
          <div class="card-block">
            <h4 class="card-title">Music Finder</h4>
            <p class="card-text">
              <a href="https://warriormuffin.github.io/new-music-finder/" class="btn btn-primary" target="_blank">Live Demo</a>
            </p>
          </div>
        </div>
        <div class="card">
          <img class="card-img-top" src="" alt="Card image cap">
          <div class="card-block">
            <h4 class="card-title">Ultimate Bravery</h4>
            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
            <p class="card-text">
              <a href="http://ultimate-bravery.herokuapp.com/#/login" class="btn btn-primary" target="_blank">Live Demo</a>
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="card-deck">
        <div class="card">
          <img class="card-img-top" src="" alt="Card image cap">
          <div class="card-block">
            <h4 class="card-title">Momentum Remake</h4>
            <p class="card-text">
              <a href="https://warriormuffin.github.io/momentum-remake/" class="btn btn-primary" target="_blank">Go somewhere</a>
            </p>
          </div>
        </div>
        <div class="card">
          <img class="card-img-top" src="" alt="Card image cap">
          <div class="card-block">
            <h4 class="card-title"></h4>
            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
            <p class="card-text">
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
nav {
  text-align: center;
}
</style>
