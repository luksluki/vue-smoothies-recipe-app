<template>
  <div class="navbar">
    <nav class="cyan darken-3">
      <div class="nav-wrapper cyan darken-3">
        <router-link :to="{name: 'Index' }">
          <a href="#" class="brand-logo">Smoothies Recipe App</a>
        </router-link>
        <ul id="nav-mobile" class="right hide-on-med-and-down">
          <li>
            <a href class="btn-floating btn-large halfway-fab pink">
              <router-link :to="{name: 'AddSmoothie'}">
                <i class="material-icons">add</i>
              </router-link>
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Nabvar",
  data() {
    return {};
  }
};
</script>

<style>
.navbar nav {
  padding: 0 20px;
}
</style>