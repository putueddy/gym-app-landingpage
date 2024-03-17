<script>
  import Conversion from "../components/Conversion.svelte";
  import FAQs from "../components/FAQ.svelte";
  import Hero from "../components/Hero.svelte";
  import Product from "../components/Product.svelte";
  import Review from "../components/Review.svelte";
</script>

<svelte:head>
  <title>Swoley Moley</title>
</svelte:head>

<main class="flex flex-col">
  <Hero />
  <Product />
  <Review />
  <FAQs />
  <Conversion />
</main>
