<template>
  <div class="navbar-container" v-bind:class="rootClassName">
    <div class="navbar-max-width">
      <nuxt-link to="/" class="navbar-navlink">
        <img
          alt="image"
          src="/whiskerlogooffbois11332-0xga-200h.png"
          class="navbar-logo"
        />
      </nuxt-link>
      <div class="navbar-links">
        <nuxt-link to="/marketplace" class="navbar-navlink1 navbar-link">
          Marketplace
        </nuxt-link>
        <a
          href="https://medium.com/@witcoinwhisker"
          target="_blank"
          rel="noreferrer noopener"
          class="navbar-link"
        >
          News
        </a>
        <a href="#RD" class="navbar-link1 navbar-link">Roadmap</a>
        <a href="#TOK" class="navbar-link2 navbar-link">Tokenomics</a>
        <a href="#SOC" class="navbar-link3 navbar-link">Social</a>
      </div>
      <div data-thq="thq-dropdown" class="navbar-thq-dropdown list-item">
        <div data-thq="thq-dropdown-toggle" class="navbar-dropdown-toggle">
          <span class="navbar-text navbar-link">Whisker</span>
          <div data-thq="thq-dropdown-arrow" class="navbar-dropdown-arrow">
            <svg viewBox="0 0 1024 1024" class="navbar-icon">
              <path d="M426 726v-428l214 214z"></path>
            </svg>
          </div>
        </div>
        <ul data-thq="thq-dropdown-list" class="navbar-dropdown-list">
          <li data-thq="thq-dropdown" class="navbar-dropdown list-item">
            <div data-thq="thq-dropdown-toggle" class="navbar-dropdown-toggle1">
              <nuxt-link to="/marketplace" class="navbar-navlink2">
                Marketplace
              </nuxt-link>
            </div>
          </li>
          <li data-thq="thq-dropdown" class="navbar-dropdown1 list-item">
            <div data-thq="thq-dropdown-toggle" class="navbar-dropdown-toggle2">
              <a
                href="https://medium.com/@witcoinwhisker"
                target="_blank"
                rel="noreferrer noopener"
                class="navbar-link4"
              >
                News
              </a>
            </div>
          </li>
          <li data-thq="thq-dropdown" class="navbar-dropdown2 list-item">
            <div data-thq="thq-dropdown-toggle" class="navbar-dropdown-toggle3">
              <a href="#RD" class="navbar-link5">Roadmap</a>
            </div>
          </li>
          <li data-thq="thq-dropdown" class="navbar-dropdown3 list-item">
            <div data-thq="thq-dropdown-toggle" class="navbar-dropdown-toggle4">
              <a href="#TOK" class="navbar-link6">Tokenimics</a>
            </div>
          </li>
          <li data-thq="thq-dropdown" class="navbar-dropdown4 list-item">
            <div data-thq="thq-dropdown-toggle" class="navbar-dropdown-toggle5">
              <a href="#SOC" class="navbar-link7">Social</a>
            </div>
          </li>
        </ul>
      </div>
      <nuxt-link to="/presale" class="navbar-cta-btn navbar-link">
        Presale
      </nuxt-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  props: {
    rootClassName: String,
  },
}
</script>

<style scoped>
.navbar-container {
  top: 0;
  width: 100%;
  display: flex;
  z-index: 1000;
  position: fixed;
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
.navbar-max-width {
  flex: 0 0 auto;
  width: 100%;
  height: 74px;
  display: flex;
  max-width: 958px;
  margin-top: 40px;
  align-items: center;
  padding-top: 10px;
  padding-left: 40px;
  padding-right: 20px;
  flex-direction: row;
  padding-bottom: 15px;
  background-size: cover;
  justify-content: space-between;
  background-image: url("/navbar2-200h.png");
  background-repeat: repeat-x;
}
.navbar-navlink {
  display: contents;
}
.navbar-logo {
  width: 50px;
  height: 50px;
  margin-top: 10px;
  object-fit: cover;
  text-decoration: none;
}
.navbar-links {
  gap: 16px;
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  flex-direction: row;
}
.navbar-navlink1 {
  margin-top: 12px;
  transition: 0.3s;
  text-decoration: none;
}
.navbar-navlink1:hover {
  color: #fddbc6;
}
.navbar-link {
  margin-top: 12px;
  transition: 0.3s;
  text-decoration: none;
}
.navbar-link:hover {
  color: #fddbc6;
}
.navbar-link1 {
  margin-top: 12px;
  transition: 0.3s;
  text-decoration: none;
}
.navbar-link1:hover {
  color: #fddbc6;
}
.navbar-link2 {
  margin-top: 12px;
  transition: 0.3s;
  text-decoration: none;
}
.navbar-link2:hover {
  color: #fddbc6;
}
.navbar-link3 {
  margin-top: 12px;
  transition: 0.3s;
  text-decoration: none;
}
.navbar-link3:hover {
  color: #fddbc6;
}
.navbar-thq-dropdown {
  cursor: pointer;
  display: none;
  position: relative;
  border-radius: var(--dl-radius-radius-radius2);
}
.navbar-dropdown-toggle {
  fill: #595959;
  color: #595959;
  width: 100%;
  display: inline-flex;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-radius2);
  padding-right: var(--dl-space-space-unit);
  padding-bottom: var(--dl-space-space-halfunit);
}
.navbar-text {
  font-style: normal;
  text-align: center;
  font-weight: 500;
  margin-right: 4px;
  vertical-align: middle;
}
.navbar-dropdown-arrow {
  transition: 0.3s;
}
.navbar-icon {
  fill: #F3b27c;
  width: 18px;
  height: 18px;
  transition: 0.3s;
}
.navbar-dropdown-list {
  left: 0%;
  width: max-content;
  display: none;
  z-index: 100;
  position: absolute;
  min-width: 100%;
  transition: 0.3s;
  align-items: stretch;
  border-color: #fde5c0;
  border-width: 1px;
  border-radius: var(--dl-radius-radius-radius4);
  flex-direction: column;
  list-style-type: none;
  list-style-position: inside;
}
.navbar-dropdown {
  cursor: pointer;
  display: inline-block;
  position: relative;
  border-radius: var(--dl-radius-radius-radius2);
}
.navbar-dropdown-toggle1 {
  fill: #fde5c0;
  color: #fde5c0;
  width: 100%;
  display: inline-flex;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-radius4);
  padding-right: var(--dl-space-space-unit);
  padding-bottom: var(--dl-space-space-halfunit);
}
.navbar-dropdown-toggle1:hover {
  fill: #fff;
  color: #fff;
  background-color: #595959;
}
.navbar-navlink2 {
  width: 100%;
  cursor: pointer;
  display: flex;
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
  text-decoration: none;
}
.navbar-dropdown1 {
  cursor: pointer;
  display: inline-block;
  position: relative;
  border-radius: var(--dl-radius-radius-radius2);
}
.navbar-dropdown-toggle2 {
  fill: #fde5c0;
  color: #fde5c0;
  width: 100%;
  display: inline-flex;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-radius4);
  padding-right: var(--dl-space-space-unit);
  padding-bottom: var(--dl-space-space-halfunit);
}
.navbar-dropdown-toggle2:hover {
  fill: #fff;
  color: #fff;
  background-color: #595959;
}
.navbar-link4 {
  width: 100%;
  cursor: pointer;
  display: flex;
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
  text-decoration: none;
}
.navbar-dropdown2 {
  cursor: pointer;
  display: inline-block;
  position: relative;
  border-radius: var(--dl-radius-radius-radius2);
}
.navbar-dropdown-toggle3 {
  fill: #fde5c0;
  color: #fde5c0;
  width: 100%;
  display: inline-flex;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-radius4);
  padding-right: var(--dl-space-space-unit);
  padding-bottom: var(--dl-space-space-halfunit);
}
.navbar-dropdown-toggle3:hover {
  fill: #fff;
  color: #fff;
  background-color: #595959;
}
.navbar-link5 {
  width: 100%;
  cursor: pointer;
  display: flex;
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
  text-decoration: none;
}
.navbar-dropdown3 {
  cursor: pointer;
  display: inline-block;
  position: relative;
  border-radius: var(--dl-radius-radius-radius2);
}
.navbar-dropdown-toggle4 {
  fill: #fde5c0;
  color: #fde5c0;
  width: 100%;
  display: inline-flex;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-radius4);
  padding-right: var(--dl-space-space-unit);
  padding-bottom: var(--dl-space-space-halfunit);
}
.navbar-dropdown-toggle4:hover {
  fill: #fff;
  color: #fff;
  background-color: #595959;
}
.navbar-link6 {
  width: 100%;
  cursor: pointer;
  display: flex;
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
  text-decoration: none;
}
.navbar-dropdown4 {
  cursor: pointer;
  display: inline-block;
  position: relative;
  border-radius: var(--dl-radius-radius-radius2);
}
.navbar-dropdown-toggle5 {
  fill: #fde5c0;
  color: #fde5c0;
  width: 100%;
  display: inline-flex;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-radius4);
  padding-right: var(--dl-space-space-unit);
  padding-bottom: var(--dl-space-space-halfunit);
}
.navbar-dropdown-toggle5:hover {
  fill: #fff;
  color: #fff;
  background-color: #595959;
}
.navbar-link7 {
  width: 100%;
  cursor: pointer;
  display: flex;
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
  text-decoration: none;
}
.navbar-cta-btn {
  fill: #402818;
  color: #402818;
  display: flex;
  transition: 0.3s;
  align-items: center;
  line-height: 1;
  padding-top: 6px;
  border-color: #3d1f10;
  border-width: 5px;
  padding-left: 8px;
  border-radius: var(--dl-radius-radius-buttonradius);
  padding-right: 8px;
  padding-bottom: 4px;
  text-decoration: none;
  background-color: rgb(171, 144, 109);
}
.navbar-cta-btn:hover {
  animation-name: pulse;
  animation-delay: 0s;
  animation-duration: 500ms;
  animation-direction: normal;
  animation-iteration-count: 1;
  animation-timing-function: ease;
}
.navbar-root-class-name {
  top: -20px;
  left: -11px;
  align-self: center;
}


@media(max-width: 1600px) {
  .navbar-max-width {
    height: 70px;
    margin-top: 40px;
  }
}
@media(max-width: 1200px) {
  .navbar-max-width {
    height: 70px;
    margin-top: 40px;
  }
}
@media(max-width: 991px) {
  .navbar-max-width {
    height: 63px;
    margin-top: 30px;
  }
}
@media(max-width: 767px) {
  .navbar-max-width {
    height: 54px;
    max-width: 500px;
    margin-top: 30px;
  }
  .navbar-links {
    display: none;
  }
  .navbar-thq-dropdown {
    display: inline-block;
  }
  .navbar-text {
    font-style: normal;
    margin-top: 11px;
    font-weight: 500;
  }
  .navbar-icon {
    width: 18px;
    margin-top: 10px;
  }
  .navbar-dropdown-list {
    border-color: #5c3f0d;
    list-style-image: url("/navbar2-200h.png");
  }
  .navbar-navlink2 {
    color: #5c3f0d;
    font-size: 14px;
    font-style: normal;
    font-weight: 500;
  }
  .navbar-link4 {
    color: #5c3f0d;
    font-size: 14px;
    font-style: normal;
    font-weight: 500;
  }
  .navbar-link5 {
    color: #5c3f0d;
    font-size: 14px;
  }
  .navbar-link6 {
    color: #5c3f0d;
    font-size: 14px;
    font-style: normal;
    font-weight: 500;
  }
  .navbar-link7 {
    color: #5c3f0d;
    font-size: 14px;
    font-style: normal;
    font-weight: 500;
  }
}
@media(max-width: 479px) {
  .navbar-max-width {
    height: 52px;
    max-width: 400px;
    margin-top: 20px;
  }
  .navbar-dropdown-list {
    border-color: #5c3f0d;
  }
  .navbar-navlink2 {
    color: #5c3f0d;
  }
  .navbar-link4 {
    color: #5c3f0d;
    font-size: 14px;
    font-style: normal;
    font-weight: 500;
  }
  .navbar-link5 {
    color: #5c3f0d;
  }
  .navbar-link6 {
    color: #5c3f0d;
  }
  .navbar-link7 {
    color: #5c3f0d;
    font-size: 14px;
    font-style: normal;
    font-weight: 500;
  }
}
</style>
