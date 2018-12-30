<template>
  <div>
    <top-header></top-header>

    <top-main></top-main>

    <top-nav></top-nav>

    <banner></banner>

    <!--<main></main>-->
  </div>
</template>

<script>
  import TopHeader from '~/components/Header'
  import TopMain from '~/components/TopMain'
  import TopNav from '~/components/Nav'
  import Banner from '~/components/Banner'
  // import Main from '~/components/Main'

  export default {
    components: {
      TopHeader,
      TopMain,
      TopNav,
      Banner,
      // Main,
    }
  }
</script>

<style>

</style>
