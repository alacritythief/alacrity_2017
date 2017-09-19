<template>
  <header>
    <div>
      <span>
        <h1 class="logo">
          ALACRITY STUDIOS
        </h1>
      </span>
      <span class="menu">
        ABOUT // VLOGS // PORTFOLIO
      </span>
    </div>
  </header>
</template>

<style lang="scss" scoped>

header {
  background-color: #000000;
  color: #ffffff;
  font-size: 1.5rem;
  padding: 0.2rem 0.5rem;
  text-align: left;
  width: 100%;
}

span {
  display: inline-block;
}

.logo {
  padding-right: 1rem;
}

.menu {
  float: right;
  padding-top: 0.4rem;
  text-align: right;
}

@media (max-width: 628px) {
  header {
    height: 5rem;
  }

  .menu {
    font-size: 1.5rem;
    padding-top: 0;
  }
}

</style>
