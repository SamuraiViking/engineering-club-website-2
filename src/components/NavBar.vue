<template>
  <div>
    <b-navbar toggleable="lg" variant="light">
      <b-navbar-brand href="#">Engineers</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#">Home</b-nav-item>
          <b-nav-item href="#">Teams</b-nav-item>
          <b-nav-item href="#">Contact</b-nav-item>
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

