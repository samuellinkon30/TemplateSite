<template>
  <b-navbar toggleable="md" type="ligth" nav class="navbar navbar-light" style="background-color: #80FF00;" >
    <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
    <div class="NameEnterprise">
      <b-navbar-brand href="Home">Sua Empresa</b-navbar-brand>
    </div>
    <div class="NameMenu">
       <b-collapse is-nav id="nav_collapse">
        <b-navbar-nav>
          <b-nav-item href="Home">Home</b-nav-item>
          <b-nav-item href="About">About</b-nav-item>
          <b-nav-item href="Services">Services</b-nav-item>
          <b-nav-item href="Contact">Contact</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </div>
  </b-navbar>
</template>

<style>
</style>

<script>
export default {
  name: 'menu'
}
</script>

<style>
.NameMenu {
  text-shadow: 0px 0px 1px gray;
}
.NameEnterprise {
  text-shadow: 1px 1px 1px gray;
}
.menu li {
  display: inline;
  margin: 0 9px;
}
.navbar {
  background: #80FF00;
  opacity: 0.65;
  padding: 10px;
  text-align: left;
}
.menu li a {
  font-family: "Poppins";
  color: #80FF00;
  text-decoration: none;
}
.brand {
  width: 100px;
  float: left;
}
body {
  background-image: url('../../assets/nature.jpg');
  background-size: cover;
}
</style>
