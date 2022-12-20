<template>
  <header>
    <div id="logo">The Bee Project</div>
    <nav>
      <span><a href="#">Home</a></span>
      <span><a href="#">Pilars</a></span>
      <span><a href="#">Projectes</a></span>
      <span><a href="https://worldbeeproject.org/">Community</a></span>
    </nav>
  </header>
</template>
  

<style lang="scss" scoped>
header {
  color: var(--color-text-header);
  height: 100px;
  background-color: black;

  display: flex;
  justify-content: space-between;
  align-items: center;

  #logo {
    font-size: 1.5rem;
    padding: 0px 5px;
  }

  span {
    padding: 0px 7px;
  }


}
</style>