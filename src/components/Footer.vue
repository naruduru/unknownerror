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
@import "../assets/scss/variables.scss";

footer {
  display: block;
  margin: 0;
  padding: 0;
  border: 0;
  font: inherit;
  font-size: 100%;
  vertical-align: baseline;
}

.site-footer * {
  box-sizing: border-box;
}

.site-footer {
  background-color: hsl(210,8%,15%);
  background-image: none;
  background-position: top left;
  background-repeat: no-repeat;
  border-top: 0;
  background-size: auto;
  color: hsl(210,8%,60%);
  padding-top: 0;
  padding-bottom: 0;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

.site-footer--container {
  max-width: $global_width;
  width: 100%;
  margin: 0 auto;
  padding: 32px 12px 12px 12px;
  display: flex;
  flex-flow: row wrap;
}

.site-footer .site-footer--logo {
  flex: 0 0 64px;
  margin: calc(12px * -1) 0 32px 0;
}

.site-footer .site-footer--nav {
  display: flex;
  flex: 2 1 auto;
  flex-wrap: wrap;
}

.site-footer .site-footer--col {
  padding: 0 12px 12px 0;
  flex: 1 0 auto;
}

.site-footer .-title {
  text-transform: uppercase;
  font-weight: bold;
  margin-bottom: 12px;
  color: hsl(210,8%,75%);
  line-height: calc((13 + 4) / 13);
}

.site-footer .-title a {
  color: hsl(210,8%,75%);
  text-decoration: none;
}

.site-footer .-list {
  margin: 0;
  list-style: none;
}

.site-footer .-link {
  color: hsl(210,8%,60%);
  padding: 4px 0;
  line-height: calc((13 + 4) / 13);
  display: inline-block;
  text-decoration: none;
}

.site-footer .site-footer--copyright {
  flex: 1 1 150px;
  display: flex;
  flex-direction: column;
}

.site-footer .site-footer--copyright ul {
  display: flex;
  list-style: none;
  margin: 0;
  padding: 0;
}

.site-footer .site-footer--copyright ul li+li {
  margin-left: 12px;
}

.site-footer .site-footer--copyright p {
  margin-top: auto;
  margin-bottom: 24px;
}

.site-footer .site-footer--copyright p a, .site-footer .site-footer--copyright p a:visited {
  line-height: inherit;
  color: var(--theme-footer-link-color);
  padding: 0;
}

.td-underline {
  text-decoration: underline !important;
}
</style>