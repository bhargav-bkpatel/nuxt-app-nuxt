<template>
  <div class="grid-card-grid-card">
    <img :alt="image_alt" :src="image_src" class="grid-card-image" />
    <span class="grid-card-text">{{ text }}</span>
    <span class="content-Light">{{ text1 }}</span>
  </div>
</template>

<script>
export default {
  name: 'GridCard',
  props: {
    text1: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet. Velit officia lorem ipsum dolor consequat duis enim velit mollit.​',
    },
    image_src: {
      type: String,
      default: 'https://play.teleporthq.io/static/svg/default-img.svg',
    },
    text: {
      type: String,
      default: 'Challange yourself',
    },
    image_alt: {
      type: String,
      default: 'image',
    },
  },
}
</script>

<style scoped>
.grid-card-grid-card {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  padding: 36px;
  align-items: flex-start;
  flex-direction: column;
  background-color: var(--dl-color-grays-white100);
}
.grid-card-image {
  width: 60px;
  height: 60px;
  object-fit: cover;
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.grid-card-text {
  font-size: 24px;
  font-style: normal;
  font-weight: 500;
  line-height: 1.3;
  margin-bottom: var(--dl-space-space-halfunit);
}
</style>
