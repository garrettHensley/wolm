<template>
  <div>
    <b-navbar toggleable="lg" class="bg">
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item>Home</b-nav-item>
          <b-nav-item-dropdown
            id="my-nav-dropdown"
            text="About"
            toggle-class="nav-link-custom text-white"
            class=""
          >
            <b-dropdown-item>Vision, Mission, & Core Values</b-dropdown-item>
            <b-dropdown-divider></b-dropdown-divider>
            <b-dropdown-item>What We Believe</b-dropdown-item>
            <b-dropdown-divider></b-dropdown-divider>
            <b-dropdown-item>Senior Leadership Team</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item>Ministries</b-nav-item>
          <b-nav-item>Events</b-nav-item>
          <b-nav-item>Live Stream</b-nav-item>
          <b-nav-item>Online Giving</b-nav-item>
          <b-nav-item>Blog</b-nav-item>
          <b-nav-item disabled>Contact Us</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.bg {
  background-color: #1a5445;
}
.bg a {
  color: white !important;
  font-weight: 400;
  font-family: "Raleway", sans-serif;
}
.navbar-dark .navbar-nav .nav-link {
  color: white !important;
}
</style>
