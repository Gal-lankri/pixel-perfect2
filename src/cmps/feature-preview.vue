<template>
  <section class='feature-preview flex column'>
    <div class="img-container">
      <img :src="getImgSrc" alt="">
    </div>
    <span>{{ feature.title }}</span>
  </section>

</template>

<script>
export default {
  name: 'feature-preview',
  props: {
    feature: {
      type: Object,
      require: true
    }
  },
  data() {
    return {}
  },
  created() { },
  methods: {},
  computed: {
    getImgSrc() {
      return `src/assets/images/icon-${this.feature.icon}.svg`
    }
  },
  components: {}
}
</script>