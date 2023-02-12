<script>
  import Footer from "../lib/footer.svelte";
  import Header from "../lib/header.svelte";


</script>

<main>
<Header/>
<slot/>
<Footer/>
</main>

<style lang="sass">
*
  font-family: 'Open Sans', sans-serif

</style>