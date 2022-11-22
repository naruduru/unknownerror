<template>
  <div id="right-side">
    <div class="s-sidebarwidget s-sidebarwidget__yellow s-anchors s-anchors__grayscale mb16">
      <ul class="d-block p0 m0">
        <li class="s-sidebarwidget--header s-sidebarwidget__small-bold-text d-flex fc-black-600 d:fc-black-900 bb bbw1">
          The Overflow Blog
        </li>
        <li class="s-sidebarwidget--item d-flex px16">
          <div>
            <svg style="width: 14px; height: 14px">
            </svg>
          </div>
          <div>
            <a>
              Hashgraph: The sustainable alternative to blockchain
            </a>
            <div>
              sponsored post
            </div>
          </div>
        </li>
        <li class="s-sidebarwidget--item d-flex px16">
          <div>
            <svg style="width: 14px; height: 14px">
            </svg>
          </div>
          <div>
            <a>
              Five Stack Exchange sites are celebrating their ten year anniversaries in Q4...
            </a>
          </div>
        </li>
        <li class="s-sidebarwidget--header s-sidebarwidget__small-bold-text d-flex fc-black-600 d:fc-black-900 bb bbw1">
          Upcoming Events
        </li>
        <li>
          <div>
            <div></div>
          </div>
          <div class="s-sidebarwidget--item d-flex px16">
            <a>2022 Community Moderator Election</a>
            <div>
              ends
              <span>November 22</span>
            </div>
          </div>
        </li>
        <li class="s-sidebarwidget--header s-sidebarwidget__small-bold-text d-flex fc-black-600 d:fc-black-900 bb bbw1">
          Featured on Meta
        </li>
        <li class="s-sidebarwidget--item d-flex px16">
          <div>
            <svg style="width: 14px; height: 14px">
            </svg>
          </div>
          <div>
            <a>
              Mobile app infrastructure being decommissioned
            </a>
          </div>
        </li>
        <li class="s-sidebarwidget--item d-flex px16">
          <div>
            <svg style="width: 14px; height: 14px">
            </svg>
          </div>
          <div>
            <a>
              The Ask Wizard (2022) has graduated
            </a>
          </div>
        </li>
        <li class="s-sidebarwidget--item d-flex px16">
          <div>
            <svg style="width: 14px; height: 14px">
            </svg>
          </div>
          <div>
            <a>
              Staging Ground Workflow: Canned Comments
            </a>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Right"
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/variables.scss";
@import "~@/assets/scss/layouts/right.scss";

@media screen and (max-width: 980px) {
  #right-side {
    float: none;
    clear: both;
    width: 100%;
    margin: 0 auto;
    background-color: aqua;
  }
}
</style>