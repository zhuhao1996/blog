<template>
  <div id="app">
    <router-link to="/">写博客</router-link>
    <router-link to="/show">博客</router-link>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
</style>
