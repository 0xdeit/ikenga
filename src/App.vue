<template>
  <div id="app">
    <header class="header">
      <h1 id="logo">Ikenga</h1>
      <ul id="nav">
        <li><a href="#" class="nav-link">Dashboard</a></li>
        <li><a href="#" class="nav-link">Profile</a></li>
        <li><a href="#" class="nav-link">Login</a></li>
      </ul>
    </header>
    <Hero hero_title="Track your time." />
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
