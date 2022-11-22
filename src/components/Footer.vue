<template>
  <footer id="footer" class="site-footer">
    <div class="site-footer--container">
      <div class="site-footer--logo">
        <img :src="require('@/assets/unknown-footer-logo.png')"/>
      </div>
      <nav class="site-footer--nav">
        <div class="site-footer--col">
          <h5 class="-title">
            <a>UNKNOWN ERROR</a>
          </h5>
          <ul class="-list">
            <li>
              <a class="-link">Questions</a>
            </li>
            <li>
              <a class="-link">Help</a>
            </li>
          </ul>
        </div>
        <div class="site-footer--col">
          <h5 class="-title">
            <a>PRODUCTS</a>
          </h5>
          <ul class="-list">
            <li>
              <a class="-link">Teams</a>
            </li>
            <li>
              <a class="-link">Advertising</a>
            </li>
            <li>
              <a class="-link">Collectives</a>
            </li>
            <li>
              <a class="-link">Talent</a>
            </li>
          </ul>
        </div>
        <div class="site-footer--col">
          <h5 class="-title">
            <a class="-link">COMPANY</a>
          </h5>
          <ul class="-list">
            <li>
              <a class="-link">About</a>
            </li>
            <li>
              <a class="-link">Press</a>
            </li>
            <li>
              <a class="-link">Work Here</a>
            </li>
            <li>
              <a class="-link">Legal</a>
            </li>
            <li>
              <a class="-link">Privacy Policy</a>
            </li>
            <li>
              <a class="-link">Terms of Service</a>
            </li>
            <li>
              <a class="-link">Contact Us</a>
            </li>
            <li>
              <a class="-link">Cookie Settings</a>
            </li>
            <li>
              <a class="-link">Cokkie Policy</a>
            </li>
          </ul>
        </div>
        <div class="site-footer--col">
          <h5 class="-title">
            <a class="-link">STACK EXCHANGE NETWORK</a>
          </h5>
          <ul class="-list">
            <li>
              <a class="-link">Technology</a>
            </li>
            <li>
              <a class="-link">Culture & recreation</a>
            </li>
            <li>
              <a class="-link">Life & arts</a>
            </li>
            <li>
              <a class="-link">Science</a>
            </li>
            <li>
              <a class="-link">Professional</a>
            </li>
            <li>
              <a class="-link">Business</a>
            </li>
            <li>
              <a class="-link">API</a>
            </li>
            <li>
              <a class="-link">Data</a>
            </li>
          </ul>
        </div>
      </nav>
      <div class="site-footer--copyright">
        <ul>
          <li><a class="-link">Blog</a></li>
          <li><a class="-link">Facebook</a></li>
          <li><a class="-link">Twitter</a></li>
          <li><a class="-link">LinkedIn</a></li>
          <li><a class="-link">Instagram</a></li>
        </ul>
        <p>
          Site design / logo © 2022 Stack Exchange Inc; user contributions licensed under
          <span class="td-underline">CC BY-SA</span>
        </p>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style lang="scss" scoped>
@import "~@/assets/scss/variables.scss";
@import "~@/assets/scss/layouts/footer.scss";
</style>