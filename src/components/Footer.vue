<template>
  <footer>
    <p>burgshop &copy; 2023</p>
  </footer>
</template>
  
<script>
export default {
  name: "Footer"
}
</script>
  
<style  scoped>
footer {
  position: fixed;
  bottom: 0;
  width: 100%;
  height: 120px;
  background-color: black;
  display: flex;
  align-items: center;
  justify-content: center;
}

p {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  color: #EFA335;
}
</style>
