<template>
  <nav>
    <router-link to="/">
      <img :src="logo" :alt="alt">
    </router-link>
    <div>
      <router-link to="/">Home</router-link>
      <router-link to="/pedidos">Pedidos</router-link>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
  props: ["logo", "alt"]
}
</script>

<style scoped>
nav {
  position: fixed;
  width: 100%;
  height: 100px;
  background-color: black;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

img {
  widows: 48px;
  height: 48px;
}

a {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 24px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  color: #EFA335;
  text-decoration: none;
  margin: 12px;
  transition: .3s;
}

a:hover {
  color: #E14649;
}
</style>
