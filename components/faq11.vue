<template>
  <div class="faq11-faq8 thq-section-padding" v-bind:class="rootClassName">
    <div class="faq11-max-width thq-section-max-width">
      <div class="thq-section-max-width thq-flex-column faq11-container">
        <div class="faq11-section-title">
          <div class="faq11-content">
            <h2 class="faq11-text thq-heading-2">{{ heading1 }}</h2>
            <p class="faq11-text1 thq-body-large">{{ content1 }}</p>
          </div>
        </div>
        <div class="faq11-list">
          <div class="faq11-faq1">
            <div @click="faq1Visible = !faq1Visible" class="faq11-trigger">
              <p class="faq11-faq1-question thq-body-large">
                When will MarketPlace be released?
              </p>
              <div class="faq11-icons-container">
                <div v-if="!faq1Visible">
                  <svg viewBox="0 0 1024 1024" class="faq11-icon">
                    <path
                      d="M213.333 554.667h256v256c0 23.552 19.115 42.667 42.667 42.667s42.667-19.115 42.667-42.667v-256h256c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-256v-256c0-23.552-19.115-42.667-42.667-42.667s-42.667 19.115-42.667 42.667v256h-256c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
                    ></path>
                  </svg>
                </div>
                <div v-if="faq1Visible">
                  <svg viewBox="0 0 1024 1024" class="faq11-icon02">
                    <path
                      d="M213.333 554.667h597.333c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-597.333c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
                    ></path>
                  </svg>
                </div>
              </div>
            </div>
            <div v-if="faq1Visible" class="faq11-container03">
              <span class="faq11-text2 thq-body-small">{{ text }}</span>
            </div>
          </div>
          <div class="faq11-faq2">
            <div @click="faq2Visible = !faq2Visible" class="faq11-trigger1">
              <p class="faq11-faq2-question thq-body-large">{{ faq2Question }}</p>
              <div class="faq11-icons-container1">
                <div v-if="!faq2Visible">
                  <svg viewBox="0 0 1024 1024" class="faq11-icon04">
                    <path
                      d="M213.333 554.667h256v256c0 23.552 19.115 42.667 42.667 42.667s42.667-19.115 42.667-42.667v-256h256c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-256v-256c0-23.552-19.115-42.667-42.667-42.667s-42.667 19.115-42.667 42.667v256h-256c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
                    ></path>
                  </svg>
                </div>
                <div v-if="faq2Visible">
                  <svg viewBox="0 0 1024 1024" class="faq11-icon06">
                    <path
                      d="M213.333 554.667h597.333c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-597.333c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
                    ></path>
                  </svg>
                </div>
              </div>
            </div>
            <div v-if="faq2Visible" class="faq11-container06">
              <span class="faq11-text3 thq-body-small">{{ text1 }}</span>
            </div>
          </div>
          <div class="faq11-faq3">
            <div @click="faq3Visible = !faq3Visible" class="faq11-trigger2">
              <p class="faq11-faq2-question1 thq-body-large">
                {{ faq3Question }}
              </p>
              <div class="faq11-icons-container2">
                <div v-if="!faq3Visible">
                  <svg viewBox="0 0 1024 1024" class="faq11-icon08">
                    <path
                      d="M213.333 554.667h256v256c0 23.552 19.115 42.667 42.667 42.667s42.667-19.115 42.667-42.667v-256h256c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-256v-256c0-23.552-19.115-42.667-42.667-42.667s-42.667 19.115-42.667 42.667v256h-256c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
                    ></path>
                  </svg>
                </div>
                <div v-if="faq3Visible">
                  <svg viewBox="0 0 1024 1024" class="faq11-icon10">
                    <path
                      d="M213.333 554.667h597.333c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-597.333c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
                    ></path>
                  </svg>
                </div>
              </div>
            </div>
            <div v-if="faq3Visible" class="faq11-container09">
              <span class="faq11-text4 thq-body-small">{{ text2 }}</span>
            </div>
          </div>
          <div class="faq11-faq4">
            <div @click="faq4Visible = !faq4Visible" class="faq11-trigger3">
              <p class="faq11-faq2-question2 thq-body-large">
                {{ faq4Question }}
              </p>
              <div class="faq11-icons-container3">
                <div v-if="!faq4Visible">
                  <svg viewBox="0 0 1024 1024" class="faq11-icon12">
                    <path
                      d="M213.333 554.667h256v256c0 23.552 19.115 42.667 42.667 42.667s42.667-19.115 42.667-42.667v-256h256c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-256v-256c0-23.552-19.115-42.667-42.667-42.667s-42.667 19.115-42.667 42.667v256h-256c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
                    ></path>
                  </svg>
                </div>
                <div v-if="faq4Visible">
                  <svg viewBox="0 0 1024 1024" class="faq11-icon14">
                    <path
                      d="M213.333 554.667h597.333c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-597.333c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
                    ></path>
                  </svg>
                </div>
              </div>
            </div>
            <div v-if="faq4Visible" class="faq11-container12">
              <span class="faq11-text5 thq-body-small">{{ text3 }}</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FAQ11',
  props: {
    heading1: {
      type: String,
      default: 'PLATFORM UNDER CONSTRUCTION',
    },
    faq1Question1: {
      type: String,
      default: 'Frequently Asked Questions',
    },
    text1: {
      type: String,
      default:
        'The NFTs will be released in the coming weeks at the end of the Backdrop Build competition. Their uses will be: GamePass for Whisker BETA, Obtain a figurine bearing the image of your NFT (Delivery costs to your account.) Eligibility for Airdrops. 3D model.',
    },
    content1: {
      type: String,
      default:
        'Whisker is a crypto initiative that aims to create a Play To Earn OpenWorld in the world of memes. It integrates the MetaVerse to bring smiles to all its inhabitants through NFT collections, tokenomics, partnerships, and a development roadmap.',
    },
    action: {
      type: String,
      default: 'Contact',
    },
    faq2Question: {
      type: String,
      default: 'When will NFTs be released and what are they used for?',
    },
    faq1Question: {
      type: String,
      default: 'What is Whisker?',
    },
    text2: {
      type: String,
      default:
        'The price of the first collection will be $35. The price will be higher for the next collections: you can read this explanatory document: https://witwhisker.com/WHISKERPRESENTATION.pdf',
    },
    rootClassName: String,
    faq4Question: {
      type: String,
      default: 'When will the Whisker BETA V1 game be released?',
    },
    heading2: {
      type: String,
      default: 'Still have a question?',
    },
    content2: {
      type: String,
      default:
        "To participate in Whisker's Play To Earn OpenWorld, you can start by acquiring Whisker tokens and exploring the various opportunities within the ecosystem. Stay updated on partnerships, events, and developments to maximize your experience.",
    },
    text3: {
      type: String,
      default:
        'The Whisker BETA v1 should be put online at the end of the BackDrop competition, at the beginning of June. This will launch our presale as well as our NFT collection.',
    },
    text: {
      type: String,
      default:
        'The simple MINT NFT platform will be available when the NFTs are released in a few weeks, then the final marketplace will be put online a few weeks later.',
    },
    faq3Question: {
      type: String,
      default: 'How much will NFTs cost?',
    },
  },
  data() {
    return {
      faq3Visible: false,
      faq1Visible: false,
      faq4Visible: false,
      faq5Visible: false,
      faq2Visible: false,
    }
  },
}
</script>

<style scoped>
.faq11-faq8 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.faq11-max-width {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.faq11-section-title {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.faq11-content {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: center;
  align-items: center;
  flex-direction: column;
}
.faq11-text {
  color: #3d1f10;
  text-align: center;
  font-family: "Star Cartoon";
}
.faq11-text1 {
  color: #3d1f10;
  text-align: center;
  font-family: "Star Cartoon";
  text-transform: uppercase;
}
.faq11-list {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: flex-start;
  flex-shrink: 0;
  flex-direction: column;
}
.faq11-faq1 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  flex-direction: column;
}
.faq11-trigger {
  display: flex;
  padding: var(--dl-space-space-unit);
  align-self: stretch;
  align-items: center;
  padding-right: 16px;
  flex-direction: row;
  justify-content: space-between;
  background-color: #fde2c0;
}
.faq11-faq1-question {
  color: #3d1f10;
  font-style: normal;
  text-align: center;
  font-family: "Star Cartoon";
  font-weight: 600;
  letter-spacing: 1px;
  text-transform: capitalize;
}
.faq11-icons-container {
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.faq11-icon {
  width: 24px;
  height: 24px;
}
.faq11-icon02 {
  width: 24px;
  height: 24px;
}
.faq11-container03 {
  display: flex;
  padding: var(--dl-space-space-unit);
  align-self: stretch;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.faq11-text2 {
  color: #9d7956;
  font-family: "Star Cartoon";
}
.faq11-faq2 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  flex-direction: column;
}
.faq11-trigger1 {
  display: flex;
  padding: var(--dl-space-space-unit);
  align-self: stretch;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
  background-color: #fde2c0;
}
.faq11-faq2-question {
  color: #3d1f10;
  font-style: normal;
  text-align: center;
  font-family: "Star Cartoon";
  font-weight: 600;
}
.faq11-icons-container1 {
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.faq11-icon04 {
  width: 24px;
  height: 24px;
}
.faq11-icon06 {
  width: 24px;
  height: 24px;
}
.faq11-container06 {
  display: flex;
  padding: var(--dl-space-space-unit);
  align-self: stretch;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.faq11-text3 {
  color: #9d7956;
  font-family: "Star Cartoon";
}
.faq11-faq3 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  flex-direction: column;
}
.faq11-trigger2 {
  display: flex;
  padding: var(--dl-space-space-unit);
  align-self: stretch;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
  background-color: #fde2c0;
}
.faq11-faq2-question1 {
  color: #3d1f10;
  font-style: normal;
  text-align: center;
  font-family: "Star Cartoon";
  font-weight: 600;
}
.faq11-icons-container2 {
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.faq11-icon08 {
  width: 24px;
  height: 24px;
}
.faq11-icon10 {
  width: 24px;
  height: 24px;
}
.faq11-container09 {
  display: flex;
  padding: var(--dl-space-space-unit);
  align-self: stretch;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.faq11-text4 {
  color: #9d7956;
  font-family: "Star Cartoon";
}
.faq11-faq4 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  border-color: var(--dl-color-theme-neutral-dark);
  border-width: 1px;
  flex-direction: column;
}
.faq11-trigger3 {
  display: flex;
  padding: var(--dl-space-space-unit);
  align-self: stretch;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
  background-color: #fde2c0;
}
.faq11-faq2-question2 {
  color: #3d1f10;
  font-style: normal;
  text-align: center;
  font-family: "Star Cartoon";
  font-weight: 600;
}
.faq11-icons-container3 {
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.faq11-icon12 {
  width: 24px;
  height: 24px;
}
.faq11-icon14 {
  width: 24px;
  height: 24px;
}
.faq11-container12 {
  display: flex;
  padding: var(--dl-space-space-unit);
  align-self: stretch;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.faq11-text5 {
  color: #9d7956;
  font-family: "Star Cartoon";
}
.faq11-root-class-name {
  top: 400px;
  left: 0px;
  position: absolute;
}
@media(max-width: 991px) {
  .faq11-container {
    flex-direction: column;
  }
}
@media(max-width: 767px) {
  .faq11-root-class-name {
    top: 600px;
  }
}
@media(max-width: 479px) {
  .faq11-max-width {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .faq11-root-class-name {
    top: 700px;
  }
}
</style>
