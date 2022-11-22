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

<style lang="scss" scoped>
@import "~@/assets/scss/variables.scss";
@import "~@/assets/scss/layouts/left.scss";

@media screen and (max-width: 640px) {
  .left-side {
    display: none;
  }
}
</style>