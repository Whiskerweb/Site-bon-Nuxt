<template>
  <div id="TOKENOMICS" class="tokenomics-tokenomics" v-bind:class="rootClassName">
    <div class="tokenomics-group11">
      <img
        :alt="rectangle3Alt"
        :src="rectangle3Src"
        class="tokenomics-rectangle3"
      />
      <img
        :alt="rectangle4Alt"
        :src="rectangle4Src"
        class="tokenomics-rectangle4"
      />
      <img
        :alt="tokenmics1Alt"
        :src="tokenmics1Src"
        class="tokenomics-tokenmics1"
      />
      <div class="tokenomics-presale">
        <img :alt="ellipse1Alt" :src="ellipse1Src" class="tokenomics-ellipse1" />
        <span class="tokenomics-text">{{ text1 }}</span>
        <span class="tokenomics-text01">{{ text2 }}</span>
        <span class="tokenomics-text02">{{ text3 }}</span>
        <span class="tokenomics-text03">{{ text4 }}</span>
      </div>
      <div class="tokenomics-dev">
        <img
          :alt="ellipse1Alt1"
          :src="ellipse1Src1"
          class="tokenomics-ellipse11"
        />
        <span class="tokenomics-text04">{{ text5 }}</span>
        <span class="tokenomics-text05">{{ text6 }}</span>
        <span class="tokenomics-text06">{{ text7 }}</span>
        <span class="tokenomics-text07">{{ text8 }}</span>
      </div>
      <div class="tokenomics-cex">
        <img
          :alt="ellipse1Alt2"
          :src="ellipse1Src2"
          class="tokenomics-ellipse12"
        />
        <span class="tokenomics-text08">{{ text9 }}</span>
        <span class="tokenomics-text09">{{ text10 }}</span>
        <span class="tokenomics-text10">{{ text11 }}</span>
        <span class="tokenomics-text11">{{ text12 }}</span>
      </div>
      <div class="tokenomics-airdrop">
        <img
          :alt="ellipse1Alt3"
          :src="ellipse1Src3"
          class="tokenomics-ellipse13"
        />
        <span class="tokenomics-text12">{{ text13 }}</span>
        <span class="tokenomics-text13">{{ text14 }}</span>
      </div>
      <div class="tokenomics-m-arketing">
        <img
          :alt="ellipse1Alt4"
          :src="ellipse1Src4"
          class="tokenomics-ellipse14"
        />
        <span class="tokenomics-text14">{{ text15 }}</span>
        <span class="tokenomics-text15">{{ text16 }}</span>
      </div>
      <div class="tokenomics-game">
        <img
          :alt="ellipse1Alt5"
          :src="ellipse1Src5"
          class="tokenomics-ellipse15"
        />
        <span class="tokenomics-text16">{{ text17 }}</span>
        <span class="tokenomics-text17">{{ text18 }}</span>
      </div>
      <div class="tokenomics-forlp">
        <span class="tokenomics-text18">{{ text19 }}</span>
        <span class="tokenomics-text19">{{ text20 }}</span>
        <img
          :alt="ellipse1Alt6"
          :src="ellipse1Src6"
          class="tokenomics-ellipse16"
        />
      </div>
      <span class="tokenomics-text20">{{ text }}</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TOKENOMICS',
  props: {
    text2: {
      type: String,
      default: '30 % For Presale :',
    },
    text3: {
      type: String,
      default: '- 5% In Airdrop',
    },
    ellipse1Alt6: {
      type: String,
      default: 'Ellipse11303',
    },
    rectangle4Alt: {
      type: String,
      default: 'Rectangle41303',
    },
    text12: {
      type: String,
      default: '- 5% for Market Making',
    },
    ellipse1Src4: {
      type: String,
      default: '/images/ellipse11303-qgo-200h.png',
    },
    ellipse1Alt2: {
      type: String,
      default: 'Ellipse11303',
    },
    text9: {
      type: String,
      default: '15 % for Exchanges  :',
    },
    tokenmics1Src: {
      type: String,
      default: '/images/tokenmics11303-415e-600w.png',
    },
    text14: {
      type: String,
      default: '15 % for Airdrops(P2A)',
    },
    text11: {
      type: String,
      default: '- 10% for CEX',
    },
    text20: {
      type: String,
      default: '15 % for LP',
    },
    text7: {
      type: String,
      default: '- 2% Developer Whisker BETA',
    },
    ellipse1Alt3: {
      type: String,
      default: 'Ellipse11303',
    },
    text19: {
      type: String,
      default: '15 % for LP',
    },
    ellipse1Src5: {
      type: String,
      default: '/images/ellipse11303-dkx-200h.png',
    },
    text4: {
      type: String,
      default: '- 25% In Airdrop',
    },
    rootClassName: String,
    text13: {
      type: String,
      default: '15 % for Airdrops(P2A)',
    },
    text10: {
      type: String,
      default: '15 % for Exchanges :',
    },
    ellipse1Src1: {
      type: String,
      default: '/images/ellipse11303-3hb7-200h.png',
    },
    text1: {
      type: String,
      default: '30 % For Presale :',
    },
    ellipse1Src: {
      type: String,
      default: '/images/ellipse11303-5blc-200h.png',
    },
    ellipse1Alt4: {
      type: String,
      default: 'Ellipse11303',
    },
    rectangle4Src: {
      type: String,
      default: '/images/rectangle41303-bzfq-1100h.png',
    },
    ellipse1Alt1: {
      type: String,
      default: 'Ellipse11303',
    },
    text18: {
      type: String,
      default: '10 % for Whisker Game',
    },
    text5: {
      type: String,
      default: '10 % For Developer :',
    },
    text15: {
      type: String,
      default: '5 % for Marketing',
    },
    text6: {
      type: String,
      default: '10 % For Developer :',
    },
    text16: {
      type: String,
      default: '5 % for Marketing',
    },
    text8: {
      type: String,
      default: '- 8% Developer Whisker GAME',
    },
    rectangle3Src: {
      type: String,
      default: '/images/rectangle31302-zyqj-1100h.png',
    },
    ellipse1Alt5: {
      type: String,
      default: 'Ellipse11303',
    },
    tokenmics1Alt: {
      type: String,
      default: 'tokenmics11303',
    },
    rectangle3Alt: {
      type: String,
      default: 'Rectangle31302',
    },
    ellipse1Src6: {
      type: String,
      default: '/images/ellipse11303-bbve.svg',
    },
    ellipse1Alt: {
      type: String,
      default: 'Ellipse11303',
    },
    text: {
      type: String,
      default: 'TOKENOMICS : 1B',
    },
    ellipse1Src2: {
      type: String,
      default: '/images/ellipse11303-jvk-200h.png',
    },
    text17: {
      type: String,
      default: '10 % for Whisker Game',
    },
    ellipse1Src3: {
      type: String,
      default: '/images/ellipse11303-2lob-200h.png',
    },
  },
}
</script>

<style scoped>
.tokenomics-tokenomics {
  width: 1381px;
  height: 753px;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-shrink: 1;
}
.tokenomics-group11 {
  top: -20px;
  left: 0px;
  right: 0px;
  width: 1418px;
  height: 828px;
  margin: auto;
  display: flex;
  position: absolute;
  align-items: flex-end;
  flex-shrink: 1;
  justify-content: flex-start;
}
.tokenomics-rectangle3 {
  top: 17px;
  left: 48px;
  width: 1325px;
  height: 775px;
  margin: auto;
  position: absolute;
  border-radius: 34px;
}
.tokenomics-rectangle4 {
  top: 28px;
  left: 60px;
  width: 1300px;
  height: 750px;
  margin: auto;
  position: absolute;
  border-radius: 34px;
}
.tokenomics-tokenmics1 {
  top: 106px;
  left: 69px;
  width: 560px;
  height: 562px;
  position: absolute;
}
.tokenomics-presale {
  top: 187px;
  left: 700px;
  width: 368px;
  height: 94px;
  display: flex;
  position: absolute;
  align-items: flex-start;
}
.tokenomics-ellipse1 {
  top: 8px;
  left: 0px;
  width: 19px;
  height: 19px;
  position: absolute;
}
.tokenomics-text {
  top: 2px;
  left: 17px;
  color: rgb(0, 0, 0);
  width: 350px;
  height: auto;
  position: absolute;
  font-size: 35px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-text01 {
  top: 0px;
  left: 18px;
  color: rgb(255, 255, 255);
  width: 350px;
  height: auto;
  position: absolute;
  font-size: 35px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-text02 {
  left: 35px;
  color: rgb(255, 255, 255);
  width: 200px;
  bottom: 23px;
  height: auto;
  position: absolute;
  font-size: 20px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-text03 {
  left: 40px;
  color: rgb(255, 255, 255);
  width: 200px;
  bottom: 0px;
  height: auto;
  position: absolute;
  font-size: 20px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-dev {
  top: 417px;
  left: 700px;
  width: 387.5px;
  height: 94px;
  display: flex;
  position: absolute;
  align-items: flex-start;
}
.tokenomics-ellipse11 {
  top: 8px;
  left: 0px;
  width: 19px;
  height: 19px;
  position: absolute;
}
.tokenomics-text04 {
  top: 2px;
  left: 31px;
  color: rgb(0, 0, 0);
  width: auto;
  height: auto;
  position: absolute;
  font-size: 35px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-text05 {
  top: 0px;
  left: 32px;
  color: #ffffff;
  width: AUTO;
  height: auto;
  position: absolute;
  font-size: 35px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-text06 {
  top: 44px;
  left: 61px;
  color: rgb(255, 255, 255);
  width: auto;
  height: auto;
  position: absolute;
  font-size: 20px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-text07 {
  left: 60px;
  color: rgb(255, 255, 255);
  width: auto;
  bottom: 0px;
  height: auto;
  position: absolute;
  font-size: 20px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-cex {
  top: 303px;
  left: 700px;
  width: 403.796875px;
  height: 91.03125px;
  display: flex;
  position: absolute;
  align-items: flex-start;
}
.tokenomics-ellipse12 {
  top: 7.875px;
  left: 0px;
  width: 20px;
  height: 19px;
  position: absolute;
}
.tokenomics-text08 {
  top: 1px;
  left: 37.09375px;
  color: rgb(0, 0, 0);
  width: auto;
  height: auto;
  position: absolute;
  font-size: 35px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-text09 {
  top: 0px;
  left: 39.09375px;
  color: rgb(255, 255, 255);
  width: auto;
  height: auto;
  position: absolute;
  font-size: 35px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-text10 {
  left: 53.09375px;
  color: rgb(255, 255, 255);
  width: 150px;
  bottom: 22px;
  height: auto;
  position: absolute;
  font-size: 20px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-text11 {
  left: 4.09375px;
  color: rgb(255, 255, 255);
  width: 350px;
  bottom: 0px;
  height: auto;
  position: absolute;
  font-size: 20px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-airdrop {
  top: 525px;
  right: 81px;
  width: 654px;
  height: 40px;
  display: flex;
  position: absolute;
  align-items: flex-start;
}
.tokenomics-ellipse13 {
  top: 8px;
  left: 16px;
  width: 20px;
  height: 19px;
  position: absolute;
}
.tokenomics-text12 {
  top: 1px;
  left: 0px;
  color: rgb(0, 0, 0);
  width: 500px;
  height: auto;
  position: absolute;
  font-size: 35px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-text13 {
  top: 0px;
  left: 2px;
  color: rgb(255, 255, 255);
  width: 500px;
  height: auto;
  position: absolute;
  font-size: 35px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-m-arketing {
  top: 594px;
  left: 700px;
  width: 359.328125px;
  height: 40px;
  display: flex;
  position: absolute;
  align-items: flex-start;
}
.tokenomics-ellipse14 {
  top: 9px;
  left: 0px;
  width: 20px;
  height: 19px;
  position: absolute;
}
.tokenomics-text14 {
  top: 1px;
  left: 33.390625px;
  color: rgb(0, 0, 0);
  width: auto;
  height: auto;
  position: absolute;
  font-size: 35px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-text15 {
  top: 0px;
  left: 35.390625px;
  color: rgb(255, 255, 255);
  width: auto;
  height: auto;
  position: absolute;
  font-size: 35px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-game {
  top: 658px;
  left: 700px;
  width: 467px;
  height: var(--dl-size-size-small);
  display: flex;
  position: absolute;
  align-items: flex-start;
}
.tokenomics-ellipse15 {
  top: 8px;
  left: 0px;
  width: 20px;
  height: 19px;
  position: absolute;
}
.tokenomics-text16 {
  top: 1px;
  left: 15px;
  color: rgb(0, 0, 0);
  width: 450px;
  height: auto;
  position: absolute;
  font-size: 35px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-text17 {
  top: 0px;
  left: 17px;
  color: rgb(255, 255, 255);
  width: 450px;
  height: 100%;
  position: absolute;
  font-size: 35px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-forlp {
  left: 700px;
  width: 264px;
  bottom: 64px;
  height: 40px;
  display: flex;
  position: absolute;
  align-items: flex-start;
}
.tokenomics-text18 {
  top: 1px;
  left: 4px;
  color: rgb(0, 0, 0);
  width: 260px;
  height: auto;
  position: absolute;
  font-size: 35px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-text19 {
  top: 0px;
  left: 35px;
  color: rgb(255, 255, 255);
  width: auto;
  height: auto;
  position: absolute;
  font-size: 35px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-ellipse16 {
  top: 8px;
  left: 0px;
  width: 20px;
  height: 19px;
  position: absolute;
}
.tokenomics-text20 {
  top: 76px;
  left: 691px;
  color: rgb(61, 31, 16);
  width: 450px;
  height: auto;
  position: absolute;
  font-size: 55px;
  box-shadow: rgba(0, 0, 0, 0.25) 0px 4px 4px 0px;
  font-style: Regular;
  text-align: center;
  font-family: Star Cartoon;
  font-weight: 400;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.tokenomics-root-class-name {
  top: 5095px;
  left: 0px;
  right: 0px;
  margin: auto;
  position: absolute;
}

@media(max-width: 1600px) {
  .tokenomics-text04 {
    top: 2px;
    left: 14px;
    right: -14px;
    width: 100%;
  }
}
@media(max-width: 1200px) {
  .tokenomics-group11 {
    top: -2px;
    left: 0px;
    right: 0px;
    width: 1200px;
    margin: auto;
  }
  .tokenomics-rectangle3 {
    top: 41px;
    right: 51px;
    width: 1100px;
    height: 600px;
    position: absolute;
  }
  .tokenomics-rectangle4 {
    top: 53px;
    left: 0px;
    right: 0px;
    width: 1080px;
    height: 580px;
    margin: auto;
  }
  .tokenomics-tokenmics1 {
    top: 112px;
    left: 79px;
    width: 445px;
    height: 446px;
    margin: auto;
  }
  .tokenomics-presale {
    top: 167px;
    left: 596px;
  }
  .tokenomics-ellipse1 {
    top: -8px;
    left: 6px;
  }
  .tokenomics-text {
    top: -10px;
    left: -25px;
    font-size: 25px;
    font-weight: normal;
  }
  .tokenomics-text01 {
    top: -12px;
    left: -23px;
    font-size: 25px;
  }
  .tokenomics-text02 {
    top: 21px;
    left: 43px;
  }
  .tokenomics-text03 {
    top: 44px;
    left: 48px;
  }
  .tokenomics-dev {
    top: 620px;
    left: 818px;
    right: -7px;
    bottom: 110px;
    position: absolute;
  }
  .tokenomics-ellipse11 {
    top: -124px;
    left: -218px;
  }
  .tokenomics-text04 {
    top: -127px;
    left: -250px;
    font-size: 25px;
  }
  .tokenomics-text05 {
    top: -128px;
    left: -182px;
    font-size: 25px;
  }
  .tokenomics-text06 {
    top: -87px;
    left: -161px;
  }
  .tokenomics-text07 {
    top: -59px;
    left: -162px;
  }
  .tokenomics-cex {
    top: 273px;
    left: 569px;
  }
  .tokenomics-ellipse12 {
    top: -31px;
    left: 31px;
  }
  .tokenomics-text08 {
    top: -34px;
    left: 69px;
    font-size: 25px;
  }
  .tokenomics-text09 {
    top: -35px;
    left: 71px;
    font-size: 25px;
  }
  .tokenomics-text10 {
    top: -2px;
    left: 86px;
  }
  .tokenomics-text11 {
    top: 22px;
    left: 36px;
  }
  .tokenomics-airdrop {
    top: 325px;
    right: -38px;
  }
  .tokenomics-text12 {
    top: 6px;
    left: -85px;
    width: 560px;
    font-size: 25px;
  }
  .tokenomics-text13 {
    top: 5px;
    left: -83px;
    width: 560px;
    font-size: 25px;
  }
  .tokenomics-m-arketing {
    top: 562px;
    left: 447px;
  }
  .tokenomics-ellipse14 {
    top: -188px;
    left: 153px;
  }
  .tokenomics-text14 {
    top: -193px;
    right: -222px;
    font-size: 25px;
  }
  .tokenomics-text15 {
    top: -194px;
    right: -224px;
    font-size: 25px;
  }
  .tokenomics-game {
    top: 409px;
    left: 546px;
  }
  .tokenomics-ellipse15 {
    top: 4px;
    left: 54px;
  }
  .tokenomics-text16 {
    font-size: 25px;
  }
  .tokenomics-text17 {
    font-size: 25px;
  }
  .tokenomics-forlp {
    left: 757px;
    bottom: 204px;
  }
  .tokenomics-text18 {
    top: -139px;
    left: -173px;
    font-size: 25px;
  }
  .tokenomics-text19 {
    top: -140px;
    left: -113px;
    font-size: 25px;
  }
  .tokenomics-ellipse16 {
    top: -136px;
    left: -157px;
  }
  .tokenomics-text20 {
    top: 77px;
    left: 600px;
    right: 194px;
  }
  .tokenomics-root-class-name1 {
    width: 100%;
  }
}
@media(max-width: 991px) {
  .tokenomics-group11 {
    top: -21px;
    left: 54px;
    width: 887px;
    height: 747px;
    margin-left: 0px;
    margin-right: 0px;
  }
  .tokenomics-rectangle3 {
    left: 0px;
    width: 877px;
    bottom: -11px;
    height: 687px;
  }
  .tokenomics-rectangle4 {
    top: 59px;
    left: 8px;
    right: 11px;
    width: 862px;
    height: 674px;
    margin-right: 0px;
    padding-bottom: 0px;
  }
  .tokenomics-tokenmics1 {
    top: 177px;
    left: 13px;
    width: 330px;
    height: 326px;
  }
  .tokenomics-presale {
    top: 221px;
    left: 328px;
  }
  .tokenomics-ellipse1 {
    top: -4px;
    left: 13px;
  }
  .tokenomics-text {
    top: -8px;
    left: -24px;
  }
  .tokenomics-text01 {
    top: -10px;
    left: -23px;
  }
  .tokenomics-text02 {
    top: 25px;
    left: 35px;
  }
  .tokenomics-text03 {
    left: 45px;
    bottom: 27px;
  }
  .tokenomics-dev {
    top: 442px;
    left: 560px;
    right: -58px;
  }
  .tokenomics-text04 {
    top: -124px;
    left: -250px;
  }
  .tokenomics-text05 {
    top: -126px;
    left: -183px;
  }
  .tokenomics-text06 {
    top: -87px;
    left: -175px;
  }
  .tokenomics-text07 {
    top: -59px;
    left: -176px;
  }
  .tokenomics-cex {
    top: 465px;
    left: 310px;
  }
  .tokenomics-text10 {
    top: 6px;
    left: 70px;
  }
  .tokenomics-text11 {
    top: 34px;
    left: 20px;
  }
  .tokenomics-airdrop {
    top: 610px;
    left: 46px;
    bottom: 101px;
  }
  .tokenomics-ellipse13 {
    top: 3px;
    left: 4px;
  }
  .tokenomics-text12 {
    top: 0px;
    left: 33px;
    width: var(--dl-size-size-xxlarge);
  }
  .tokenomics-text13 {
    top: -1px;
    left: 35px;
    width: var(--dl-size-size-xxlarge);
  }
  .tokenomics-m-arketing {
    top: 650px;
    left: 18px;
    bottom: 63px;
  }
  .tokenomics-ellipse14 {
    top: 5px;
    left: 33px;
    margin: auto;
  }
  .tokenomics-text14 {
    top: 3px;
    left: 0px;
    right: 0px;
    margin: auto;
  }
  .tokenomics-text15 {
    top: 2px;
    left: 2px;
    right: -1px;
    width: 100%;
    margin: auto;
  }
  .tokenomics-game {
    top: 519px;
    left: 12px;
  }
  .tokenomics-ellipse15 {
    top: 40px;
    left: 38px;
    bottom: -15px;
  }
  .tokenomics-text16 {
    top: 38px;
    left: -4px;
    bottom: -21px;
    margin: auto;
  }
  .tokenomics-text17 {
    top: 37px;
    left: -3px;
    bottom: -37px;
    margin: auto;
  }
  .tokenomics-forlp {
    right: -32px;
    width: 167px;
    bottom: -101px;
    padding-left: 0px;
  }
  .tokenomics-text18 {
    top: -118px;
    left: -730px;
  }
  .tokenomics-text19 {
    top: -119px;
    left: -670px;
  }
  .tokenomics-ellipse16 {
    top: -116px;
    left: -706px;
  }
  .tokenomics-text20 {
    top: 95px;
    left: 203px;
  }
}
@media(max-width: 767px) {
  .tokenomics-group11 {
    top: -13px;
    left: 0px;
    right: 0px;
    width: 767px;
    margin: auto;
  }
  .tokenomics-rectangle3 {
    top: 37px;
    left: -12px;
    right: -4px;
    width: 724px;
    height: 706px;
  }
  .tokenomics-rectangle4 {
    left: 0px;
    right: 40px;
    width: 700px;
    bottom: 6px;
    height: 700px;
  }
  .tokenomics-tokenmics1 {
    top: 135px;
    left: 63px;
    width: 298px;
    height: 298px;
  }
  .tokenomics-presale {
    top: 169px;
    left: 350px;
    margin: auto;
  }
  .tokenomics-ellipse1 {
    top: 5px;
    left: 3px;
  }
  .tokenomics-text {
    top: 4px;
    left: -28px;
  }
  .tokenomics-text01 {
    top: 2px;
    left: -27px;
  }
  .tokenomics-text02 {
    top: 46px;
    left: 27px;
  }
  .tokenomics-text03 {
    top: 65px;
    left: 32px;
    bottom: 5px;
  }
  .tokenomics-dev {
    top: 250px;
    left: 572px;
    right: -189px;
    margin: auto;
  }
  .tokenomics-text04 {
    top: -127px;
    left: -249px;
  }
  .tokenomics-text06 {
    top: -84px;
    left: -160px;
  }
  .tokenomics-text07 {
    top: -56px;
    left: -160px;
  }
  .tokenomics-cex {
    top: 423px;
    left: 320px;
    right: 53px;
  }
  .tokenomics-text10 {
    top: 6px;
    left: 88px;
  }
  .tokenomics-text11 {
    top: 36px;
    left: 39px;
  }
  .tokenomics-airdrop {
    top: 506px;
    left: 78px;
  }
  .tokenomics-text12 {
    top: 1px;
    left: 37px;
    width: auto;
    text-align: left;
  }
  .tokenomics-text13 {
    top: 0px;
    left: 39px;
    width: auto;
    text-align: left;
  }
  .tokenomics-m-arketing {
    top: 558px;
    left: 79px;
    width: 125px;
    margin-right: 0px;
  }
  .tokenomics-ellipse14 {
    top: 4px;
    left: 4px;
    margin: auto;
  }
  .tokenomics-text14 {
    top: 0px;
    left: 8px;
    width: var(--dl-size-size-xxlarge);
    margin: auto;
  }
  .tokenomics-text15 {
    top: 0px;
    left: 10px;
    width: var(--dl-size-size-xxlarge);
    margin: auto;
  }
  .tokenomics-game {
    top: 648px;
    left: 54px;
  }
  .tokenomics-ellipse15 {
    top: -36px;
    left: 30px;
  }
  .tokenomics-text16 {
    top: -39px;
    left: -21px;
  }
  .tokenomics-text17 {
    top: -115px;
    left: -19px;
  }
  .tokenomics-forlp {
    top: 653px;
    left: 111px;
  }
  .tokenomics-text18 {
    top: 0px;
    left: -56px;
    bottom: 0px;
    margin: auto;
  }
  .tokenomics-text19 {
    top: 0px;
    left: 4px;
    bottom: 0px;
    margin: auto;
  }
  .tokenomics-ellipse16 {
    top: 5px;
    left: -25px;
    margin: auto;
  }
  .tokenomics-text20 {
    top: 67px;
    left: 55px;
  }
}
@media(max-width: 479px) {
  .tokenomics-group11 {
    top: 0px;
    left: 0px;
    right: 0px;
    width: 374px;
    bottom: 0px;
    height: 831px;
    margin: auto;
    margin-top: auto;
    padding-top: 0px;
    justify-content: center;
  }
  .tokenomics-rectangle3 {
    top: 0px;
    left: 0px;
    right: 0px;
    width: 385px;
    bottom: 0px;
    height: 1024px;
    margin: auto;
  }
  .tokenomics-rectangle4 {
    top: 0px;
    left: 0px;
    right: 0px;
    width: 379px;
    bottom: 0px;
    height: 1019px;
    margin: auto;
  }
  .tokenomics-tokenmics1 {
    top: 20px;
    left: 41px;
    width: 299px;
    height: 299px;
    margin: auto;
  }
  .tokenomics-presale {
    top: 462px;
    left: 25px;
    right: -22px;
  }
  .tokenomics-ellipse1 {
    top: 10px;
    left: 16px;
    position: absolute;
  }
  .tokenomics-text {
    top: 9px;
    left: -19px;
  }
  .tokenomics-text01 {
    top: 7px;
    left: -18px;
  }
  .tokenomics-text02 {
    top: 51px;
    left: 73px;
    width: auto;
    margin: auto;
  }
  .tokenomics-text03 {
    left: 52px;
    width: 200px;
    bottom: -28px;
    height: var(--dl-size-size-small);
    margin: auto;
  }
  .tokenomics-dev {
    top: 520px;
    left: 35px;
    right: -55px;
  }
  .tokenomics-ellipse11 {
    top: 6px;
    left: 2px;
    margin: auto;
  }
  .tokenomics-text04 {
    top: 5px;
    left: -35px;
  }
  .tokenomics-text05 {
    top: 3px;
    left: 33px;
  }
  .tokenomics-text06 {
    top: 39px;
    left: -65px;
    right: 0px;
    width: auto;
    margin: auto;
    font-size: 15px;
    text-align: center;
  }
  .tokenomics-text07 {
    top: 64px;
    left: 55px;
    font-size: 15px;
    text-align: center;
  }
  .tokenomics-cex {
    top: 384px;
    left: 13px;
  }
  .tokenomics-text11 {
    top: 39px;
    left: 36px;
  }
  .tokenomics-airdrop {
    top: 840px;
    left: 30px;
    right: -2px;
    width: 341px;
    bottom: -42px;
    height: 59px;
  }
  .tokenomics-ellipse13 {
    top: 11px;
    left: 10px;
    margin: auto;
  }
  .tokenomics-text12 {
    top: 8px;
    left: 40px;
    width: auto;
    margin: auto;
  }
  .tokenomics-text13 {
    top: 6px;
    left: 42px;
    margin: auto;
  }
  .tokenomics-m-arketing {
    top: 670px;
    left: 39px;
    right: 6px;
    width: 327px;
    bottom: 85px;
  }
  .tokenomics-ellipse14 {
    top: 4px;
    left: 2px;
    margin: auto;
  }
  .tokenomics-text14 {
    top: -190px;
    left: -13px;
    right: 25px;
    width: 100%;
    bottom: -4px;
    height: 100%;
    margin: auto;
    margin-top: 190px;
  }
  .tokenomics-text15 {
    top: -190px;
    left: -11px;
    right: 50px;
    width: 100%;
    bottom: 50px;
    height: 100%;
    margin: auto;
    position: absolute;
    margin-top: 190px;
  }
  .tokenomics-game {
    top: 700px;
    left: 23px;
    bottom: 34px;
  }
  .tokenomics-ellipse15 {
    top: 2px;
    left: 17px;
    width: 21px;
    height: 20px;
    margin: auto;
  }
  .tokenomics-text16 {
    top: 40px;
    left: -39px;
    width: 100%;
    bottom: 0px;
    height: 100%;
    margin: auto;
  }
  .tokenomics-text17 {
    top: -1px;
    left: -75px;
    right: 0px;
    width: 100%;
    margin: auto;
  }
  .tokenomics-forlp {
    top: 800px;
    left: 16px;
    bottom: -17px;
  }
  .tokenomics-text18 {
    top: 9px;
    left: -3px;
    margin: auto;
  }
  .tokenomics-text19 {
    top: 7px;
    left: 45px;
    right: LEFT;
    width: 100%;
    bottom: -8px;
    height: 100%;
    margin: auto;
  }
  .tokenomics-ellipse16 {
    top: 11px;
    left: 25px;
    margin: auto;
  }
  .tokenomics-text20 {
    top: -56px;
    left: -34px;
    margin: auto;
    font-size: 40px;
  }
}
</style>
