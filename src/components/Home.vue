<template>
  <main>
    <div class="wrapper">
      <h2>About</h2>
      <p>
        Front end JavaScript developer with Fine Art BA (Hons) from MMU. Learnt
        to code at Northcoders full stack bootcamp in 2018. Volunteer teaching
        assistant and mentor at Code Your Future. Avid follower of the Agile
        Manifesto.
      </p>
    </div>
    <div class="wrapper">
      <h2>Technical</h2>
      <ul>
        <li>JavaScript, HTML5, CSS3, Sass, GraphQL</li>
        <li>jQuery, React, React Testing Library, Cypress</li>
        <li>VWO, Adobe Target, Google Optimize, Monetate</li>
        <li>Magento, Shopify</li>
      </ul>
    </div>
    <div class="wrapper">
      <h2>Experience</h2>
      <ul>
        <li>MAGO</li>
        <li>Ampersand</li>
        <li>The Fragrance Shop</li>
        <li>JD Sports</li>
        <li>Code Computerlove</li>
      </ul>
    </div>
    <div class="wrapper">
      <h2>Diversity</h2>
      <p>
        I take inclusion in tech very seriously. My pronouns are She/Her. I
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
  justify-content: space-around;
  text-align: center;
}

.wrapper {
  width: 100%;
}

@media only screen and (min-width: 600px) {
  .wrapper {
    width: 45%;
  }
}

@media only screen and (min-width: 992px) {
  .wrapper {
    width: 24%;
  }
}
</style>
