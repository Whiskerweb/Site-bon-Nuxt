<template>
  <div class="teleport-hq-footer-teleport-hq-footer" v-bind:class="rootClassName">
    <div class="teleport-hq-footer-container">
      <div class="teleport-hq-footer-container1">
        <span class="teleport-hq-footer-text">{{ text }}</span>
        <svg viewBox="0 0 1024 1024" class="teleport-hq-footer-icon">
          <path
            d="M512 854q140 0 241-101t101-241-101-241-241-101-241 101-101 241 101 241 241 101zM512 86q176 0 301 125t125 301-125 301-301 125-301-125-125-301 125-301 301-125zM506 390q-80 0-80 116v12q0 116 80 116 30 0 50-17t20-43h76q0 50-44 88-42 36-102 36-80 0-122-48t-42-132v-12q0-82 40-128 48-54 124-54 66 0 104 38 42 42 42 98h-76q0-14-6-26-10-20-14-24-20-20-50-20z"
          ></path>
        </svg>
        <span class="teleport-hq-footer-text1">{{ text1 }}</span>
      </div>
      <a
        :href="linkTeleportHQ"
        target="_blank"
        rel="noreferrer noopener"
        class="teleport-hq-footer-link"
      >
        <div class="teleport-hq-footer-teleport-hq">
          <span class="teleport-hq-footer-text2">{{ text2 }}</span>
          <img
            alt="TeleportHQ logo"
            src="/logo-teleporthq-200w-200w.webp"
            class="teleport-hq-footer-image"
          />
        </div>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TeleportHQFooter',
  props: {
    linkTeleportHQ: {
      type: String,
      default: 'https://www.teleporthq.io',
    },
    text1: {
      type: String,
      default: '2024 All rights reserved.',
    },
    text: {
      type: String,
      default: 'Copyright',
    },
    imageAlt: {
      type: String,
      default: 'TeleportHQ logo',
    },
    text2: {
      type: String,
      default: 'Made in TeleportHQ',
    },
    imageSrc: {
      type: String,
      default: '89bee4e0-1327-4c2e-9fe9-df441bef4697',
    },
    rootClassName: String,
  },
}
</script>

<style scoped>
.teleport-hq-footer-teleport-hq-footer {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-fourunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fourunits);
}
.teleport-hq-footer-container {
  display: flex;
  font-size: 16px;
  align-items: center;
  flex-direction: row;
}
.teleport-hq-footer-container1 {
  display: flex;
  align-items: center;
  flex-direction: row;
}
.teleport-hq-footer-text {
  fill: #fff;
  color: #fff;
  margin-right: var(--dl-space-space-halfunit);
}
.teleport-hq-footer-icon {
  fill: var(--dl-color-gray-white);
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-halfunit);
}
.teleport-hq-footer-text1 {
  fill: #fff;
  color: #fff;
}
.teleport-hq-footer-link {
  display: contents;
}
.teleport-hq-footer-teleport-hq {
  display: flex;
  align-items: center;
  padding-left: 4px;
  flex-direction: row;
  text-decoration: none;
}
.teleport-hq-footer-text2 {
  fill: #fff;
  color: #fff;
  margin-right: var(--dl-space-space-halfunit);
}
.teleport-hq-footer-image {
  width: 25px;
  object-fit: cover;
}


@media(max-width: 767px) {
  .teleport-hq-footer-text {
    fill: var(--dl-color-gray-white);
    color: var(--dl-color-gray-white);
  }
  .teleport-hq-footer-text1 {
    fill: var(--dl-color-gray-white);
    color: var(--dl-color-gray-white);
  }
  .teleport-hq-footer-text2 {
    fill: var(--dl-color-gray-white);
    color: var(--dl-color-gray-white);
  }
}
@media(max-width: 479px) {
  .teleport-hq-footer-container {
    flex-direction: column;
  }
}
</style>
