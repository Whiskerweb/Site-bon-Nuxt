<template>
  <div class="logos1-container thq-section-padding" v-bind:class="rootClassName">
    <div class="logos1-max-width thq-section-max-width">
      <h2 class="logos1-text thq-heading-2">{{ heading1 }}</h2>
      <div class="thq-grid-6">
        <img
          :alt="logo1Alt"
          :src="logo1Src"
          class="logos1-logo1 thq-img-ratio-16-9"
        />
        <img
          :alt="logo2Alt"
          :src="logo2Src"
          class="logos1-logo2 thq-img-ratio-16-9"
        />
        <img
          :alt="logo3Alt"
          :src="logo3Src"
          class="logos1-logo3 thq-img-ratio-16-9"
        />
        <img
          :alt="logo4Alt"
          :src="logo4Src"
          class="logos1-logo4 thq-img-ratio-16-9"
        />
        <img
          :alt="logo5Alt"
          :src="logo5Src"
          class="logos1-logo5 thq-img-ratio-16-9"
        />
        <img
          :alt="logo6Alt"
          :src="logo6Src"
          class="logos1-logo6 thq-img-ratio-16-9"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Logos1',
  props: {
    logo6Alt: {
      type: String,
      default: 'Roadmap Logo',
    },
    logo4Alt: {
      type: String,
      default: 'Tokenomics Logo',
    },
    logo2Alt: {
      type: String,
      default: 'NFT Collections Logo',
    },
    logo3Src: {
      type: String,
      default: '/design%20sans%20titre%20(19)-1400w.png',
    },
    logo3Alt: {
      type: String,
      default: 'Marketplace Logo',
    },
    logo1Src: {
      type: String,
      default: '/design%20sans%20titre%20(20)-1400w.png',
    },
    heading1: {
      type: String,
      default: 'Whisker - Play To Earn OpenWorld',
    },
    logo2Src: {
      type: String,
      default: '/design%20sans%20titre%20(18)-1400w.png',
    },
    logo1Alt: {
      type: String,
      default: 'Whisker Logo',
    },
    logo5Src: {
      type: String,
      default: '/design%20sans%20titre%20(22)-1400w.png',
    },
    logo6Src: {
      type: String,
      default: '/design%20sans%20titre%20(17)-1400w.png',
    },
    rootClassName: String,
    logo4Src: {
      type: String,
      default: '/design%20sans%20titre%20(21)-1400w.png',
    },
    logo5Alt: {
      type: String,
      default: 'Partnerships Logo',
    },
  },
}
</script>

<style scoped>
.logos1-container {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
}
.logos1-max-width {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.logos1-text {
  color: #3d1f10;
  text-align: center;
  font-family: "Star Cartoon";
}
.logos1-logo1 {
  object-fit: contain;
}
.logos1-logo2 {
  object-fit: contain;
}
.logos1-logo3 {
  object-fit: contain;
}
.logos1-logo4 {
  object-fit: contain;
}
.logos1-logo5 {
  object-fit: contain;
}
.logos1-logo6 {
  object-fit: contain;
}
.logos1-root-class-name {
  top: 100px;
  left: 0px;
  position: absolute;
  background-color: #ffffff;
}
@media(max-width: 767px) {
  .logos1-container {
    gap: var(--dl-space-space-twounits);
  }
  .logos1-max-width {
    gap: var(--dl-space-space-twounits);
  }
}
</style>
