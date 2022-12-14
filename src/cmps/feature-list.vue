<template>
  <section class='feature-list '>
    <ul class="card-grid">
      <li v-for="feature in features" :key="feature.title">
        <feature-preview :feature="feature" />
      </li>
    </ul>
  </section>
</template>


<script>
import featurePreview from './feature-preview.vue';

export default {
  name: 'feature-list',
  props: [],
  data() {
    return {
      features: [
        { icon: 'access-anywhere', title: 'Access your files, anywhere' },
        { icon: 'security', title: 'Security you can trust' },
        { icon: 'collaboration', title: 'Real-time collaboration' },
        { icon: 'any-file', title: 'Store any type of file' },
      ]
    }
  },
  created() { },
  methods: {},
  computed: {},
  components: {
    featurePreview
  }
}
</script>