<template>
  <header>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href="#">NavBar</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav class="main-nav">
        <b-navbar-nav align="left">start</b-navbar-nav>
        <b-navbar-nav align="center">center</b-navbar-nav>
        <b-navbar-nav align="right">end</b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </header>
</template>

<style scoped>
header {
  height: 800px;
  border: 1px solid black;
  background-image: url('~assets/img/img.jpg');
}
.main-nav {
  display: flex;
  justify-content: space-between;
}
</style>