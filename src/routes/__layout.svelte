<script>
  import CallToAction from "$lib/callToAction/CallToAction.svelte";
  import Footer from "$lib/footer/Footer.svelte";
  import Header from "$lib/header/Header.svelte";
  import "../theme/_style.scss";
</script>

<Header />

<main>
  <slot />
</main>

<!-- <CallToAction />

<Footer /> -->
<style lang="scss">
</style>
