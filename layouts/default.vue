<template>
  <div id="app">
    <nav>
      <!-- <router-link to="/"><Button type="primary">Home</Button></router-link> |
      <router-link to="/about"><Button type="primary">About</Button></router-link> -->
      <NuxtLink to="/">
        <el-button type="primary">
          Home
        </el-button>
      </NuxtLink> |
      <NuxtLink to="/about">
        <el-button type="primary">
          About
        </el-button>
      </NuxtLink>
    </nav>
    <Nuxt />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
