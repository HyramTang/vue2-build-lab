<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/form">Form</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="less">
#app {
  text-align: center;
}

#nav {
  padding: 30px;
}
</style>
