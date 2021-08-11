<template>
  <main>
    <div class="wrapper about">
      <h2>About</h2>
      <p>
        Front end JavaScript developer based in Manchester. I have a Fine Art BA
        (Hons) from MMU but learnt to code at Northcoders full stack bootcamp in
        2018. In my spare time I volunteer as a teaching assistant at Code Your
        Future.
      </p>
    </div>
    <div class="wrapper technical">
      <h2>Technical</h2>
      <ul>
        <li>JavaScript, HTML5, CSS3, Sass, GraphQL</li>
        <li>jQuery, React, React Testing Library, Cypress</li>
        <li>VWO, Adobe Target, Google Optimize, Monetate</li>
        <li>Magento, Shopify</li>
      </ul>
    </div>
    <div class="wrapper resume">
      <h2>Resume</h2>
      <ul>
        <li>MAGO</li>
        <li>Ampersand</li>
        <li>The Fragrance Shop</li>
        <li>JD Sports</li>
        <li>Code Computerlove</li>
      </ul>
    </div>
    <div class="wrapper diversity">
      <h2>Diversity</h2>
      <p>
        My pronouns are She/Her. I take inclusion in tech very seriously and
        would love to speak at your meetup. My previous talks include
        "Microaggressions in the workplace" and "Breaking into the industry as a
        gender minority".
      </p>
    </div>
  </main>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
main {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
  margin: 16px;
  flex: 1;
  color: #ffffff;
}

.wrapper {
  width: 100%;
  padding: 8px 16px;
  margin-bottom: 16px;
}

@media only screen and (min-width: 600px) {
  .wrapper {
    width: 40%;
  }
}

@media only screen and (min-width: 992px) {
  .wrapper {
    width: 20%;
  }
}

.about {
  background-color: #fb5607;
}

.technical {
  background-color: #ff006e;
}

.resume {
  background-color: #8338ec;
}

.diversity {
  background-color: #3a86ff;
}

li {
  margin-bottom: 8px;
}
</style>
