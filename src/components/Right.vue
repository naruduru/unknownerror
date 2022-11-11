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
        <li>
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
        <li>
          Upcoming Events
        </li>
        <li>
          <div>
            <div></div>
          </div>
          <div>
            <a>2022 Community Moderator Election</a>
            <div>
              ends
              <span>November 22</span>
            </div>
          </div>
        </li>
        <li>
          Featured on Meta
        </li>
        <li>
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
        <li>
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
        <li>
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
        <li>
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

<style scoped>
#right-side {
  float: right;
  width: 300px;
  margin: 0 0 15px;
}

@media screen and (max-width: 980px) {
  #right-side {
    float: none;
    clear: both;
    width: 100%;
    margin: 0 auto;
    background-color: aqua;
  }
}

.mb16 {
  margin-bottom: 16px !important;
}

.s-sidebarwidget {
  --s-sidebarwidget-content-padding: calc(16px - 1px);
  --s-sidebarwidget-content-inner-spacing: 12px;
  --s-sidebarwidget-content-outer-spacing: 16px;
  --s-sidebarwidget-outer-border-color: hsl(210,8%,85%);
  --s-sidebarwidget-content-separator-color: hsl(210,8%,95%);
  --s-sidebarwidget-header-background-color: hsl(210,8%,97.5%);
  position: relative;
  border: 1px solid hsl(210,8%,85%);
  border-radius: 3px;
  box-shadow: 0 1px 2px hsla(0,0%,0%,0.05), 0 1px 4px hsla(0, 0%, 0%, 0.05), 0 2px 8px hsla(0, 0%, 0%, 0.05);
  font-size: 13px;
  background-color: hsl(0,0%,100%);
}

.s-sidebarwidget__yellow {
  border-color: hsl(47,65%,84%);
  background-color: hsl(47,87%,94%);
}

.d-block {
  display: block !important;
}

.p0 {
  padding: 0 !important;
}

.m0 {
  margin: 0 !important;
}

ul {
  list-style-type: disc;
}

ol, ul {
  list-style: none;
}

.s-sidebarwidget__yellow .s-sidebarwidget--header, .s-sidebarwidget__yellow .s-sidebarwidget--content {
  border-color: hsl(47,65%,84%);
}

.s-sidebarwidget__yellow .s-sidebarwidget--header {
  background-color: hsl(47,83%,91%);
  color: hsl(210,8%,25%);
}

.s-sidebarwidget--header.s-sidebarwidget__small-bold-text {
  font-size: 12px;
  font-weight: bold;
}

.s-sidebarwidget--header:first-child {
  border-top-left-radius: 3px;
  border-top-right-radius: 3px;
}

.d-flex {
  display: flex !important;
}

.fc-black-600, .h\:fc-black-600:hover, .f\:fc-black-600:focus, .f\:fc-black-600:focus-within {
  color: hsl(210,8%,35%) !important;
}

.bbw1 {
  border-bottom-width: 1px !important;
}

.bb {
  border-bottom-style: solid !important;
  border-bottom-width: 1px !important;
}

.s-sidebarwidget--header {
  padding: 12px calc(16px - 1px);
  background: var(--s-sidebarwidget-header-background-color);
  color: hsl(210,8%,35%);
  font-size: 1.15384615rem;
  font-weight: normal;
  margin: 0;
}

.s-sidebarwidget--header, .s-sidebarwidget--content {
  border-top: 1px solid var(--s-sidebarwidget-content-separator-color);
}

.d-flex {
  display: flex !important;
}
.px16 {
  padding-left: 16px !important;
  padding-right: 16px !important;
}
.s-sidebarwidget--item {
  margin: var(--s-sidebarwidget-content-inner-spacing) 0;
}
</style>