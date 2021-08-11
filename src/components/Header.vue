<template>
  <nav>
    <h1>Mand Cashin</h1>
    <ul>
      <li>
        <a href="https://github.com/RazzBerryMand/" target="_blank">Github</a>
      </li>
      <li>
        <a href="https://codepen.io/razzberrymand" target="_blank">Codepen</a>
      </li>
      <li>
        <a href="https://www.linkedin.com/in/mandcashin/" target="_blank"
          >Linkedin</a
        >
      </li>
      <li>
        <a href="https://www.instagram.com/razzberrymand/" target="_blank"
          >Instagram</a
        >
      </li>
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
  font-size: 32px;
}

ul {
  display: flex;
  flex-direction: row;
}

a {
  text-decoration: none;
  padding: 8px;
  cursor: pointer;
  color: #000000;
}

a:hover {
  background-color: #ffbe0b;
}
</style>
