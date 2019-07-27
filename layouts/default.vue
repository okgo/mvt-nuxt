<template lang="pug">
  div
    app-header
    nuxt
    app-footer
</template>
<script>
  import AppHeader from "@/components/Header";
  import AppFooter from "@/components/Footer";

  export default {
    components: {
      AppHeader,
      AppFooter
    },
  }
</script>
