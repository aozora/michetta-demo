<template>
  <div id="layout">
    <site-header></site-header>
    <main>
      <router-view class="view"></router-view>
    </main>
    <site-footer></site-footer>
  </div>
</template>

<script>
import SiteHeader from '@components/SiteHeader';
import SiteFooter from '@components/SiteFooter';

export default {
  components: [
    SiteHeader,
    SiteFooter
  ]
};
</script>
