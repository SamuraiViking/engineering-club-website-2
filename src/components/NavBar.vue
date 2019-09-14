<template>
  <div>
    <b-navbar toggleable="lg" variant="light">
      <b-navbar-brand href="#">Engineers</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item>
            <a class="nav-link" href="#about" v-smooth-scroll>About</a>
          </b-nav-item>
          <b-nav-item>
            <a class="nav-link" href="#meet-the-team" v-smooth-scroll>The Team</a>
          </b-nav-item>
          <b-nav-item>
            <a class="nav-link" href="#contact" v-smooth-scroll>Contact</a>
          </b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item>
            <font-awesome-icon :icon="['fab', 'facebook-square']" size="2x" />
          </b-nav-item>

          <b-nav-item>
            <font-awesome-icon :icon="['fab', 'github']" size="2x" />
          </b-nav-item>
          <b-nav-item>
            <font-awesome-icon :icon="['fab', 'youtube']" size="2x" />
          </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
  export default {
    name: "nav-bar"
  }
</script>

<style>

.nav-link {
  color: rgba(0, 0, 0, 0.5);
}
</style>

