<template>
  <div class="cta1-container thq-section-padding" v-bind:class="rootClassName">
    <div class="cta1-max-width thq-section-max-width">
      <div class="cta1-content">
        <h2 class="cta1-heading1 thq-heading-2">{{ heading1 }}</h2>
        <div class="cta1-actions">
          <button class="cta1-button thq-button-filled">
            <span class="cta1-action1 thq-body-small">{{ action1 }}</span>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CTA1',
  props: {
    content1: {
      type: String,
      default:
        'Become a part of the Whisker community and stay updated on the latest developments, NFT drops, and exciting gameplay opportunities.',
    },
    rootClassName: String,
    heading1: {
      type: String,
      default: 'Ready to dive into the world of memes?',
    },
    action1: {
      type: String,
      default: 'Home',
    },
    action2: {
      type: String,
      default: 'Explore Whisker Marketplace',
    },
  },
}
</script>

<style scoped>
.cta1-container {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  overflow: hidden;
  position: relative;
  flex-direction: column;
}
.cta1-max-width {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  flex-direction: column;
}
.cta1-content {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.cta1-heading1 {
  color: #f3c285;
  text-align: center;
  font-family: "Star Cartoon";
}
.cta1-actions {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
}
.cta1-button {
  text-decoration: none;
  background-color: #f3c285;
}
.cta1-action1 {
  text-align: center;
}
.cta1-root-class-name {
  align-self: flex-start;
  background-size: cover;
  background-image: url("/designsanstitre1211331-83hq-200h.png");
}
@media(max-width: 479px) {
  .cta1-actions {
    width: 100%;
    flex-direction: column;
  }
  .cta1-button {
    width: 100%;
  }
}
</style>
