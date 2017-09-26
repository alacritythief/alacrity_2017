<template>
  <section class="container">
    <div class="content">
      <h2>
        ANDY WONG
      </h2>
      <br>
      <ul class="about-blurb">
        <li class="blurb-first">Web Developer + Illustrator</li>
        <li class="blurb-link">Senior Web Engineer <a href="">@CogoLabs</a></li>
        <li class="blurb-link">Graduate of <a href="">@LaunchAcademy</a></li>
        <li class="blurb-link">Occasionaly <a href="">Vlogs on YouTube</a></li>
        <li class="social-links">
          <a href=""><span class="icon-twitter-squared"></span></a>
          <a href=""><span class="icon-linkedin-squared"></span></a>
          <a href=""><span class="icon-github-squared"></span></a>
          <a href=""><span class="icon-youtube-squared"></span></a>
          <a href=""><span class="icon-instagram"></span></a>
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

ul.about-blurb li {
  background-color: #000000;
  color: #ffffff;
  clear: right;
  display: inline-block;
  float: right;
}

li.blurb-first {
  padding-left: 0.2rem;
  padding-right: 0.2rem;
}

li.blurb-link {
  padding-left: 0.2rem;
}

li.blurb-link a {
  color: red;
  padding-right: 0.2rem;
}

li.blurb-link a:hover {
  background-color: #ffffff;
  color: #000000;
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

.social-links a {
  color: #ffffff;
}

.social-links a:hover {
  background-color: #ffffff;
  color: #000000;
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

  .social-links a {
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
