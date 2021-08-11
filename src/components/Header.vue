<template>
  <nav>
    <h1>Mand Cashin</h1>
    <ul>
      <li><a>Github</a></li>
      <li><a>Codepen</a></li>
      <li><a>Linkedin</a></li>
      <li><a>Instagram</a></li>
    </ul>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
nav {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 100%;
}

@media only screen and (min-width: 600px) {
  nav {
    flex-direction: row;
    justify-content: space-between;
  }
}

h1 {
  padding: 8px;
  margin: 0;
}

ul {
  display: flex;
  flex-direction: row;
}

li {
  padding: 8px;
}
</style>
