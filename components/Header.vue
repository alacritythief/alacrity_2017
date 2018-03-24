<template>
  <header>
    <div>
      <span>
        <h1 class="logo">
          ALACRITY STUDIOS
        </h1>
      </span>
      <span class="menu">
        <a href="https://github.com/alacritythief">GITHUB</a> // <a href="https://www.youtube.com/user/alacritythief">VLOGS</a> // <a href="http://portfolio.alacritystudios.com/">ILLUSTRATION</a>
      </span>
    </div>
  </header>
</template>

<style lang="scss" scoped>

header {
  background-color: #000000;
  border-bottom: 2px solid #333333;
  color: #ffffff;
  font-size: 1rem;
  padding: 0.2rem 0.5rem;
  text-align: left;
  width: 100%;
}

span {
  display: inline-block;
}

a:hover {
  text-decoration: underline;
}

.logo {
  padding-right: 1rem;
}

.menu {
  float: right;
  font-size: 1.5rem;
  padding-top: 0.3rem;
  text-align: right;
}

.menu a {
  color: #ffffff;
}

// Media sizing for mobile

@media (max-width: 598px) {
  header {
    height: 4.7rem;
  }

  .menu {
    padding-top: 0;
  }
}

</style>
