<template>
  <header class="top-bar">
    <div class="top-bar--container">
      <a class="top-bar-logo">
        <span class="logo-img"><img :src="require('@/assets/unknown-logo.png')"/></span>
      </a>
      <ol class="navigation">
        <li>
          <a class="navigation--item">About</a>
        </li>
        <li>
          <a class="navigation--item">Products</a>
        </li>
        <li>
          <a class="navigation--item">For Teams</a>
        </li>
      </ol>
      <form class=".s-topbar .s-topbar--searchbar">
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
@import "../assets/scss/variables.scss";
.top-bar {
  position: fixed !important;
  left: 0 !important;
  top: 0 !important;
  min-width: auto;
  width: 100%;
  z-index: 5050;
  background-color: $black-025;
  display: flex;
  align-items: center;
  height: 50px;
  margin: 0;
  padding: 0;
  vertical-align: baseline;
}

.top-bar--container {
  width: 97.2307692rem;
  max-width: 100%;
  height: 100%;
  display: flex;
  margin: 0 auto;
  align-items: center;
  padding: 0;
  border: 0;
}

.top-bar-logo {
  padding: 0 calc(8px * 1);
  height: 100%;
  display: flex;
  align-items: center;
  background-color: transparent;
}

.logo-img {
  margin-left: 0;
  width: 190px;
  height: 30px;
}

.navigation {
  display: flex;
  margin: calc(2px * -1);
  padding: 2px 0;
  flex-wrap: wrap;
  list-style: none;
}

li {
  margin: 0;
  padding: 0;
}

.navigation--item {
  display: flex;
  align-items: center;
  padding: 6px 12px;
  position: relative;
  border: none;
  background: none;
  box-shadow: none;
  cursor: pointer;
  user-select: auto;
  border-radius: 1000px;
  margin: 2px;
  white-space: nowrap;
}

.s-input {
  width: 100%;
  margin: 0;
  padding: 0.6em 0.7em;
  border: 1px solid $black-200;
  border-radius: 3px;
  font-size: 13px;
  font-family: inherit;
}

.h100 {
  height: 100% !important;
}
.overflow-x-auto {
  overflow-x: auto !important;
  scrollbar-color: var(--scrollbar) transparent;
}
.pr12 {
  padding-right: var(--su12) !important;
}
.ml-auto {
  margin-left: auto !important;
}

.top-bar--content {
  display: flex;
  height: 100%;
  list-style: none;
  margin: 0;
  padding: 0;
  overflow-x: auto;
}

.top-bar--content > li {
  display: inline-flex;
  margin: 0;
  padding: 0;
  border: 0;
}

.top-bar--item {
  align-self: center;
  padding-top: 8px;
  padding-bottom: 8px;
  color: $powder-700;
  background-color: $powder-100;
  border-color: $powder-500;
  box-shadow: inset 0 1px 0 0 hsl(0deg 0% 100% / 70%);
}

.s-btn {
  position: relative;
  display: inline-block;
  padding: 0.8em;
  border: 1px solid transparent;
  border-radius: 3px;
  outline: none;
  font-family: inherit;
  font-size: 13px;
  font-weight: normal;
  line-height: calc((13 + 2) / 13);
  text-align: center;
  text-decoration: none;
  cursor: pointer;
  user-select: none;
  border-color: $powder-500;
}

.ml4 {
  margin-left: 4px !important;
}

.s-btn__primary {
  color: $white;
  background-color: $blue-500;
  box-shadow: inset 0 1px 0 0 hsl(0deg 0% 100% / 40%);
}

.top-bar--searchbar--input-group {
  position: relative;
  flex-grow: 1;
}
</style>