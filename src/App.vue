<template>
  <nav class="navbar navbar-light">
    <div class="container">
      <a class="navbar-brand disabled" href="#">KafeinArt's</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <router-link to="/" class="nav-link" aria-current="page">
              Home
            </router-link>
          </li>
          <li class="nav-item">
            <router-link to="/about" class="nav-link"> About </router-link>
          </li>
          <li class="nav-item">
            <router-link to="/gallery" class="nav-link"> Gallery </router-link>
          </li>
          <li class="nav-item">
            <router-link to="/cosplayer" class="nav-link"> Cosplayer </router-link>
          </li>
          <li class="nav-item">
            <router-link to="/contact" class="nav-link"> Contact </router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <router-view />
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
#app {
  padding-top: 0.45rem;
  font-family: 'Press Start 2P', cursive; 
  color: #2c3e50;
}

nav {
  padding: 30px;
  margin-bottom: 2rem;
}
nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #1991c9;
}
</style>
