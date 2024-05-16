<template>
  <div class="privacy-policy-container">
    <div class="privacy-policy-cta2">
      <app-cta1 rootClassName="cta1-root-class-name"></app-cta1>
    </div>
    <div class="privacy-policy-contentlist3">
      <content-list1
        rootClassName="content-list1-root-class-name"
      ></content-list1>
    </div>
    <app-baspage rootClassName="baspage-root-class-name2"></app-baspage>
    <div class="privacy-policy-footer4"></div>
  </div>
</template>

<script>
import AppCta1 from '../components/cta1'
import ContentList1 from '../components/content-list1'
import AppBaspage from '../components/baspage'

export default {
  name: 'PrivacyPolicy',
  props: {},
  components: {
    AppCta1,
    ContentList1,
    AppBaspage,
  },
  head: {
    title: 'PrivacyPolicy - exported project',
    meta: [
      {
        property: 'og:title',
        content: 'PrivacyPolicy - exported project',
      },
    ],
  },
}
</script>

<style scoped>
.privacy-policy-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  background-color: #e8d6c6;
}
.privacy-policy-cta2 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.privacy-policy-contentlist3 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.privacy-policy-footer4 {
  flex: 0 0 auto;
  width: 100%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
