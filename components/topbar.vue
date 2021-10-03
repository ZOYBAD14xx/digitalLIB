<template>
  <b-navbar toggleable="lg" type="light" variant="light">
    <b-navbar-brand href="/"><b>HORSAMOUD</b></b-navbar-brand>
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
    <b-collapse id="nav-collapse" is-nav>
      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-navbar-nav>
<div class="nav_items">
          <b-navbar-nav>
     <b-nav-item href="/"> News </b-nav-item>
          <b-nav-item href="/blog">Blog</b-nav-item>
          <b-nav-item href="/book"> Book</b-nav-item>
          <b-nav-item href="/service">Service</b-nav-item>
          <b-nav-item href="/about"> About </b-nav-item>
          </b-navbar-nav>
</div>

          <b-nav-item href="#">
            <b-button variant="success">Register</b-button>
          </b-nav-item>
          <b-nav-item href="/auth/login">
            <b-button variant="outline-success">Login</b-button>
          </b-nav-item>
        </b-navbar-nav>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {};
</script>

<style>
.nav_items{
  margin-top: 8px;
}
</style>
