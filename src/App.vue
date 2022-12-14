
<template>
  <section class="app-main">
    <app-header />
    <hero/>
    <feature-list/>
    <stay-productive/>
    <app-footer/>
  </section>
</template>

<script>
import appHeader from './cmps/app-header.vue'
import appFooter from './cmps/app-footer.vue';
import appMain from './cmps/app-main.vue'
import hero from './cmps/hero.vue'
import featureList from './cmps/feature-list.vue'
import stayProductive from './cmps/stay-productive.vue';
export default {
  components: {
    appHeader,
    appFooter,
    hero,
    featureList,
    stayProductive
  }

}
</script>

