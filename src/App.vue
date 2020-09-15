<template>
  <div id="app">
    <header>
      <h1 id="logo">Ikenga</h1>
      <nav>
        <ul>
          <li><a href="#" class="nav-link">Dashboard</a></li>
          <li><a href="#" class="nav-link">Profile</a></li>
          <li><a href="#" class="nav-link">Login</a></li>
        </ul>
      </nav>
    </header>
    <Hero hero_title="Track your time." />
    <div class="flex-container">
      <div class="highlights">
        <div class="highlight-item">
          <h2>highlight title</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. A magnam
            veritatis natus vitae sed corporis ipsam architecto quia temporibus
            accusamus?
          </p>
          <a href="#">Read more...</a>
        </div>
        <div class="highlight-item">
          <h2>highlight title</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. A magnam
            veritatis natus vitae sed corporis ipsam architecto quia temporibus
            accusamus?
          </p>
          <a href="#">Read more...</a>
        </div>
        <div class="highlight-item">
          <h2>highlight title</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. A magnam
            veritatis natus vitae sed corporis ipsam architecto quia temporibus
            accusamus?
          </p>
          <a href="#">Read more...</a>
        </div>
      </div>
    </div>
    <div class="separator"></div>
    <div class="flex-container">
      <div class="highlights">
        <div class="highlight-item">
          <h2>highlight title</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. A magnam
            veritatis natus vitae sed corporis ipsam architecto quia temporibus
            accusamus?
          </p>
          <a href="#">Read more...</a>
        </div>
        <div class="highlight-item">
          <h2>highlight title</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. A magnam
            veritatis natus vitae sed corporis ipsam architecto quia temporibus
            accusamus?
          </p>
          <a href="#">Read more...</a>
        </div>
        <div class="highlight-item">
          <h2>highlight title</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. A magnam
            veritatis natus vitae sed corporis ipsam architecto quia temporibus
            accusamus?
          </p>
          <a href="#">Read more...</a>
        </div>
      </div>
    </div>

    <footer>
      <p>Created by <a href="https://roosterhead.dev">roosterhead</a>.</p>
      <p><a href="https://github.com/0xdeit/ikenga">Github</a></p>
    </footer>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Dashboard from "./components/Dashboard.vue";
import Hero from "./components/Hero.vue";

@Component({
  components: {
    Dashboard,
    Hero
  }
})
export default class App extends Vue {}
</script>

<style lang="scss">
@import "./styles/global.scss";
@import "./styles/App.scss";
</style>
