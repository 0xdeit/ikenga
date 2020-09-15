<template>
  <div class="hero">
    <h1 class="hero-title">{{ hero_title }}</h1>
    <a href="#"><button class="btn-border-white">Learn more</button></a>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Hero extends Vue {
  @Prop() private hero_title!: string;
}
</script>

<style lang="scss">
@import "../styles/global.scss";
@import "../styles/Hero.scss";
</style>
