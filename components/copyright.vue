<template>
  <div class="copyright-copyright">
    <div class="copyright-max-width max-content-container">
      <span class="copyright-text">
        <span class="copyright-text1">
          © All rights reserved
          <span v-html="rawjdh8"></span>
        </span>
       
          <span class="copyright-text2">@Bhargav</span>
     </span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Copyright',
  props: {},

  data() {
    return {
      rawjdh8: ' ',
      rawiwb2: ' ',
      raw7sjo: ' ',
    }
  },
}
</script>

<style scoped>
.copyright-copyright {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-twounits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-twounits);
}
.copyright-max-width {
  align-items: stretch;
}
.copyright-text {
  color: var(--dl-color-grays-gray100);
  font-size: 14px;
  font-style: normal;
  font-weight: 300;
  line-height: 1.5;
}
.copyright-text1 {
  font-style: normal;
  font-weight: 300;
}
.copyright-text2 {
  font-style: normal;
  font-weight: 300;
  text-decoration: underline;
}
.copyright-text3 {
  font-style: normal;
  font-weight: 300;
}
.copyright-text4 {
  font-style: normal;
  font-weight: 300;
  text-decoration: underline;
}
.copyright-text5 {
  font-style: normal;
  font-weight: 300;
}
.copyright-text6 {
  font-style: normal;
  font-weight: 300;
  text-decoration: underline;
}
.copyright-text7 {
  font-style: normal;
  font-weight: 300;
}
@media(max-width: 991px) {
  .copyright-max-width {
    flex-direction: column;
  }
}
</style>
