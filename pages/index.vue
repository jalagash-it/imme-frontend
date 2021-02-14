<template>
  <b-container fluid>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href="#">NavBar</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav class="main-nav">
        <b-navbar-nav align="left">start</b-navbar-nav>
        <b-navbar-nav align="center">center</b-navbar-nav>
        <b-navbar-nav align="right">end</b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <CatalogSlider />
    <SalesSlider />
    <PrivatePolice/>
  </b-container>
</template>

<script>
import CatalogSlider from "~/components/CatalogSlider";
import SalesSlider from "~/components/SalesSlider";
import PrivatePolice from "~/components/PrivatePolice";

export default {
  components: {
    CatalogSlider,
    SalesSlider,
  },
};
</script>

<style scoped>
body {
  margin: 0;
  font-family: "Montserrat";
}
.container-fluid {
  padding: 0;
  margin: 0;
}
.main-nav {
  display: flex;
  justify-content: space-between;
}
img {
  max-width: 100%;
  height: auto;
}
</style>

 