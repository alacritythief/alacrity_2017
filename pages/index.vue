<template>
  <section class="container">
    <div class="content">
      <h2>
        ANDY WONG
      </h2>
      <br>
      <ul class="about-blurb">
        <li>Web Developer + Illustrator.</li>
        <li>Senior Web Engineer @CogoLabs.</li>
        <li>Graduate of @LaunchAcademy.</li>
        <li>Occasionaly Vlogs on YouTube.</li>
        <li class="social-links">
          <span class="icon-twitter-squared"></span>
          <span class="icon-linkedin-squared"></span>
          <span class="icon-github-squared"></span>
          <span class="icon-youtube-squared"></span>
          <span class="icon-instagram"></span>
        </li>
      </ul>
    </div>
  </section>
</template>

<style lang="scss" scoped>

h2 {
  background-color: #ffffff;
  display: inline-block;
  padding: 0.1rem 0.5rem;
  margin-bottom: 0.3rem;
}

li {
  background-color: #000000;
  color: #ffffff;
  padding: 0.1rem 0.5rem;
  display: inline-block;
  float: right;
  clear: right;
}

.container {
  height: 100%;
}

.content {
  background-image: url('~assets/img/desk.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: 48%;
  height: 100vh;
  width: 100%;
  text-align: right;
}

.social-links {
  font-size: 1.5rem;
  margin-top: 0.3rem;
  padding: 1px 0;
}

// MOBILE
@media (max-width: 1000px) {
  .content {
    font-size: 1rem;
    padding: 0.5rem;
  }
}

@media (max-width: 600px) {
  .content {
    font-size: 1rem;
    padding: 0.5rem;
  }

  .social-links span {
    float: right;
    clear: right;
  }
}

// SCREENS
@media (min-width: 1001px) {
  .content {
    padding: 2rem;
    font-size: 1.5rem;
  }
}

</style>
