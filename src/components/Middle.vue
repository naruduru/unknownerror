<template>
  <div class="middle">
    <div class="d-flex fw-wrap mb12">
      <h1 class="fl1">All Questions</h1>
      <div>
        <a class="s-btn__primary s-btn"> Ask Question</a>
      </div>
    </div>
    <div>
      <div>
        <div>
          23,199,059 questions
        </div>
        <div>
          <div>
            <div>
              <a>Newest</a>
              <a>Active</a>
              <a>Bountied</a>
              <a>Unanswered</a>
              <button>More</button>
            </div>
            <div>Filter</div>
          </div>
        </div>
        <div id="questions">
          <div id="question-summary">
            <div>
              <div>
                <span>2</span>
                <span>votes</span>
              </div>
              <div>
                <span>1</span>
                <span>answer</span>
              </div>
              <div>
                <span>273</span>
                <span>views</span>
              </div>
            </div>
            <div>
              <h3>
                <a>Failed to connect to remote machine. Verify the SSH service connection details. All configured authentication methods failed</a>
              </h3>
            </div>
            <div>
              My SSH configuration for Azure pipeline worked fine until I upgraded ubuntu from Ubuntu20 to Ubuntu 22. Now I get this message:
              ##[error]Failed to connect to the remote machine. Verify the SSH service ...
            </div>
            <div>
              <div>
                <ul>
                  <li>
                    <a>ssh</a>
                  </li>
                  <li>
                    <a>azure-pipelines</a>
                  </li>
                </ul>
              </div>
              <div>
                <div>
                  <a>
                    <div>
                      <img />
                    </div>
                  </a>
                </div>
                <div>
                  <div>
                    <a>Jeremy Caney</a>
                  </div>
                  <ul>
                    <li>
                      <span>6,672</span>
                    </li>
                  </ul>
                </div>
                <time>
                  <a>
                    modified
                  </a>
                  <span>1 min ago</span>
                </time>
              </div>
            </div>
          </div>
        </div>
        <br class="clear-both">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Middle"
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/variables.scss";
.middle {
  width: calc(100% - 300px - 24px);
  float: left;
  background-color: $global_background_color;
}

@media screen and (max-width: 980px) {
  .middle {
    width: 100%;
    float: none;
    background-color: pink;
  }
}

.d-flex {
  display: flex !important;
}

.mb12 {
  margin-bottom: 12px !important;
}

.fw-wrap {
  flex-wrap: wrap !important;
}

.fl1 {
  flex: 1 auto !important;
}

.s-btn__primary {
  color: $white;
  background-color: $blue-500;
  box-shadow: inset 0 1px 0 0 hsl(0deg 0% 100% / 40%);
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
</style>