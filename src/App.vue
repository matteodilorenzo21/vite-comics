<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppProviders from './components/AppProviders.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  name: "Vite Comics",
  components: {AppHeader, AppMain, AppProviders, AppFooter },
  data() {
    return {}
  }
}
</script>

<template>
<AppHeader />
<AppMain />
<AppProviders />
</template>

<style lang="scss">
@use './assets/scss/style.scss'
</style>