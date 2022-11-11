<template>
  <div class="left-side">
    <div class="left-side--sticky-container">
      <nav class="left-side-nav">
        <ol class="nav-links">
          <li class="ps-relative">
            <a class="pl8 nav-links--link">
              <div class="d-flex ai-center">
                <div class="truncate">
                  HOME
                </div>
              </div>
            </a>
          </li>
          <li>
            <ol class="nav-links">
              <li class="fs-fine tt-uppercase ml8 mt16 mb4 fc-light">
                PUBLIC
              </li>
              <li>
                <ol class="nav-links">
                  <li class="ps-relative">
                    <a class="nav-links--link">
                      <div class="d-flex ai-center">
                        <div class="truncate">
                          Questions
                        </div>
                      </div>
                    </a>
                  </li>
                  <li class="ps-relative">
                    <a class="nav-links--link">
                      <div class="d-flex ai-center">
                        <div class="truncate">
                          Tags
                        </div>
                      </div>
                    </a>
                  </li>
                  <li class="ps-relative">
                    <a class="nav-links--link">
                      <div class="d-flex ai-center">
                        <div class="truncate">
                          Users
                        </div>
                      </div>
                    </a>
                  </li>
                  <li class="ps-relative">
                    <a class="nav-links--link">
                      <div class="d-flex ai-center">
                        <div class="truncate">
                          Companies
                        </div>
                      </div>
                    </a>
                  </li>
                </ol>
              </li>
            </ol>
          </li>
          <li class="ps-relative">
            <a class="pl8 nav-links--link">
              <div class="d-flex ai-center">
                <div class="truncate">
                  COLLECTIVES
                </div>
              </div>
            </a>
          </li>
          <li class="ps-relative">
            <a class="pl8 nav-links--link">
              <div class="d-flex ai-center">
                <div class="truncate">
                  Explore Collectives
                </div>
              </div>
            </a>
          </li>
          <li>
            <ol class="nav-links">
              <li class="ps-relative">
                <div class="fs-fine tt-uppercase ml8 mt16 mb8 fc-light">
                  TEAMS
                </div>
                <div class="bt bl bb bc-black-075 p12 pb6 fc-black-600 blr-sm overflow-hidden">
                  <strong class="fc-black-750 mb6">Stack Overflow for Teams</strong>
                  - Start collaborating and sharing organizational knowledge.
                </div>
              </li>
            </ol>
          </li>
        </ol>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "Left"
}
</script>

<style scoped>
.left-side {
  width: 164px;
  flex-shrink: 0;
  z-index: 1000;
  position: relative !important;
}

@media screen and (max-width: 640px) {
  .left-side {
    display: none;
  }
}

.left-side--sticky-container {
  position: sticky;
  width: auto;
  overflow-y: auto;
  max-height: calc(100vh - 50px);
  top: 24px;
  margin-bottom: 8px;
  padding-top: 24px;
}

.left-side-nav {
  display: block;
}

.nav-links {
  padding: 0;
  margin: 0 0 12px;
  list-style: none;
}

.ps-relative {
  position: relative !important;
}

.nav-links .nav-links--link, .nav-links .nav-links--link:visited {
  color: hsl(210,8%,35%);
}

.nav-links .nav-links--link {
  display: block;
  padding: 4px;
  padding-left: 30px;
  line-height: 2;
  font-size: 13px;
}

.d-flex {
  display: flex !important;
}

.ai-center {
  align-items: center !important;
}

.truncate {
  overflow: hidden;
  max-width: 100%;
  text-overflow: ellipsis !important;
  white-space: nowrap;
}

.tt-uppercase {
  text-transform: uppercase !important;
}

.fc-light {
  color: hsl(210,8%,45%) !important;
}

.fs-fine {
  font-size: 11px !important;
}

.ml8 {
  margin-left: 8px !important;
}

.mb8 {
  margin-bottom: 8px !important;
}

.mt16 {
  margin-top: 16px !important;
}

.overflow-hidden {
  overflow: hidden !important;
}

.pb6 {
  padding-bottom: 6px !important;
}
.p12 {
  padding: 12px !important;
}
.fc-black-600, .h\:fc-black-600:hover, .f\:fc-black-600:focus, .f\:fc-black-600:focus-within {
  color: hsl(210,8%,35%) !important;
}
.bc-black-2, .bc-black-075 {
  border-color: hsl(210,8%,90%) !important;
}
.blr-sm {
  border-top-left-radius: 3px !important;
  border-bottom-left-radius: 3px !important;
}
.bl {
  border-left-style: solid !important;
  border-left-width: 1px !important;
}
.bb {
  border-bottom-style: solid !important;
  border-bottom-width: 1px !important;
}
.bt {
  border-top-style: solid !important;
  border-top-width: 1px !important;
}

.mb6 {
  margin-bottom: 6px !important;
}

.fc-black-750, .h\:fc-black-750:hover, .f\:fc-black-750:focus, .f\:fc-black-750:focus-within {
  color: hsl(210,8%,20%) !important;
}

b, strong {
  font-weight: bold;
}

.pl8 {
  padding-left: 8px !important;
}

.tt-uppercase {
  text-transform: uppercase !important;
}

.mb4 {
  margin-bottom: 4px !important;
}
</style>