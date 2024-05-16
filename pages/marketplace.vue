<template>
  <div class="marketplace-container">
    <app-navbar rootClassName="navbar-root-class-name1"></app-navbar>
    <div class="marketplace-logos3">
      <app-logos1 rootClassName="logos1-root-class-name"></app-logos1>
    </div>
    <div class="marketplace-faq5">
      <app-faq11
        content1="The MINT NFT platform as well as the gaming platform will be found on this page, it is currently under construction."
        rootClassName="faq11-root-class-name"
      ></app-faq11>
    </div>
    <div class="marketplace-footer6"></div>
  </div>
</template>

<script>
import AppNavbar from '../components/navbar'
import AppLogos1 from '../components/logos1'
import AppFaq11 from '../components/faq11'

export default {
  name: 'MARKETPLACE',
  props: {},
  components: {
    AppNavbar,
    AppLogos1,
    AppFaq11,
  },
  head: {
    title: 'MARKETPLACE - exported project',
    meta: [
      {
        property: 'og:title',
        content: 'MARKETPLACE - exported project',
      },
    ],
  },
}
</script>

<style scoped>
.marketplace-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.marketplace-logos3 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  position: relative;
  align-items: center;
  justify-content: center;
}
.marketplace-faq5 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  position: relative;
  align-items: center;
  margin-bottom: 287px;
  justify-content: center;
}
.marketplace-footer6 {
  flex: 0 0 auto;
  width: 100%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
