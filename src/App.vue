<template>
  <div id="app">
<!--    <div id="nav">-->
<!--      <router-link to="/">Home</router-link> |-->
<!--      <router-link to="/about">About</router-link>-->
<!--    </div>-->
    <router-view/>
  </div>
</template>

<style lang="scss">
  @import "./styles/common/index";

  #app {
    min-height: 100%;
    max-width: $screen-lg;
    padding: {
      left: $indent-medium;
      right: $indent-medium;
    };
    margin: {
      left: auto;
      right: auto;
    };
    display: flex;

    > * {
      min-width: 100%;
    }
  }
</style>
