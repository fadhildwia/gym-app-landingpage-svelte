<script>
  import FAQs from "./../components/FAQs.svelte"
  import Hero from "../components/Hero.svelte"
  import Product from "../components/Product.svelte"
  import Reviews from "../components/Reviews.svelte"
  import Conversion from "../components/Conversion.svelte"
</script>

<svelte:head>
    <title>Swoley Moley</title>
</svelte:head>

<main class="flex flex-col">
  <Hero />
  <Product />
  <Reviews />
  <FAQs />
  <Conversion />
</main>
