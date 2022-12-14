

<template>
  <section class="app-main">
    <app-header />
    <intro/>
    <app-footer />
  </section>
</template>

<script>
import appHeader from './cmps/app-header.vue'
import appFooter from './cmps/app-footer.vue';
import appMain from './cmps/app-main.vue'
import intro from './cmps/intro.vue'
export default {
  components: {
    appHeader,
    appFooter,
    intro
  }

}
</script>

