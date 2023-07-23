<template>
  <div class="spotify">
    <div class="header">
      <div class="into-header">
        <button class="sign-up">
          <b>Sign Up</b>
        </button>
        <button class="log-in">
          <b>Log In</b>
        </button>
      </div>
    </div>
    <div class="menu">
      <div class="home">
        <button>
          <i class="bi bi-house-door"></i><b>Home</b>
        </button>
        <button>
          <i class="bi bi-search"></i><b>Search</b>
        </button>
      </div>
      <div class="library">
        <div class="library-buttons">
          <button>
            <i class="bi bi-collection-fill"></i><b>Your Library</b>
          </button>
          <button class="more">
            <i class="bi bi-plus"></i>
          </button>
        </div>
        <div class="playlist">
          <span>Create your first playlist</span>
          <span id="help">It's easy, we'll help you</span>
          <button><b>Create playlist</b></button>
        </div>
        <button id="lang"><i class="bi bi-globe"></i>English</button>
      </div>
    </div>
    <div class="cards">
      <button class="card">
        <img src="../assets/natura.jpg" alt="">
        <div class="name">
          <b>Nature</b>
        </div>
        <div class="description">
          <b>Incredible sounds</b>
        </div>
      </button>
      <button class="card">
        <img src="../assets/studio.jpg" alt="">
        <div class="name">
          <b>Instrumental Study</b>
        </div>
        <div class="description">
          <b>Soft study music</b>
        </div>
      </button>
      <button class="card">
        <img src="../assets/hiphop.jpg" alt="">
        <div class="name">
          <b>Hip Hop</b>
        </div>
        <div class="description">
          <b>Best of Hip Hop</b>
        </div>
      </button>
      <button class="card">
        <img src="../assets/rock.jpg" alt="">
        <div class="name">
          <b>Rock</b>
        </div>
        <div class="description">
          <b>Best of Rock</b>
        </div>
      </button>
      <button class="card">
        <img src="../assets/sleep.jpg" alt="">
        <div class="name">
          <b>Sleep</b>
        </div>
        <div class="description">
          <b>Fall asleep with this</b>
        </div>
      </button>
      <button class="card">
        <img src="../assets/2020.jpg" alt="">
        <div class="name">
          <b>All Out 2020s</b>
        </div>
        <div class="description">
          <b>Biggest songs of 2020s</b>
        </div>
      </button>
      <button class="card">
        <img src="../assets/2010.jpg" alt="">
        <div class="name">
          <b>All Out 2010s</b>
        </div>
        <div class="description">
          <b>Biggest songs of 2010s</b>
        </div>
      </button>
      <button class="card">
        <img src="../assets/focus.jpg" alt="">
        <div class="name">
          <b>Focus Flow</b>
        </div>
        <div class="description">
          <b>Beats to help you focus</b>
        </div>
      </button>
      <button class="card">
        <img src="../assets/piano.jpg" alt="">
        <div class="name">
          <b>Peaceful Piano</b>
        </div>
        <div class="description">
          <b>Piano songs</b>
        </div>
      </button>
      <button class="card">
        <img src="../assets/mix.jpg" alt="">
        <div class="name">
          <b>Daily Mix</b>
        </div>
        <div class="description">
          <b>Your daily mix</b>
        </div>
      </button>
    </div>
  </div>
</template>

<script>
import '../assets/styles/components/spotify.scss'
export default {
  name: 'HelloWorld',
  props: {
  }
}
</script>