<template>
  <header class="top-bar">
    <div class="top-bar--container">
      <a class="top-bar-logo">
        <span class="logo-img"><img :src="require('@/assets/unknown-logo.png')"/></span>
      </a>
      <ol class="navigation">
        <li class="md:d-none">
          <a class="navigation--item">About</a>
        </li>
        <li>
          <a class="navigation--item">Products</a>
        </li>
        <li class="md:d-none">
          <a class="navigation--item">For Teams</a>
        </li>
      </ol>
      <form class="s-top-bar s-top-bar--searchbar">
        <div class="top-bar--searchbar--input-group">
          <input class="s-input"/>
        </div>
      </form>
      <nav class="h100 ml-auto overflow-x-auto pr12">
        <ol class="top-bar--content">
          <li>
            <a class="s-btn top-bar--item">Login</a>
          </li>
          <li>
            <a class="s-btn__primary s-btn top-bar--item ml4">Sign up</a>
          </li>
        </ol>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style lang="scss" scoped>
@import "~@/assets/scss/variables.scss";
@import "~@/assets/scss/layouts/header.scss";

@media screen and (max-width: 980px) {
  .md\:d-none {
    display: none !important;
  }
}
</style>