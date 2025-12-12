<script lang="ts">
  import TopBanner from "$lib/components/TopBanner.svelte";
  import Navbar from "$lib/components/Navbar.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import Intro from "$lib/components/Intro.svelte";
  import Carousel from "$lib/components/Carousel.svelte";
  import ValueProp from "$lib/components/ValueProp.svelte";
  import ShowroomGrid from "$lib/components/ShowroomGrid.svelte";
  import Steps from "$lib/components/Steps.svelte";
  import Features from "$lib/components/Features.svelte";
  import Illustration from "$lib/components/Illustration.svelte";
  import Sustainability from "$lib/components/Sustainability.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<svelte:head>
  <title>OnPoint Companies | Boston Luxury Real Estate Development</title>
  <meta name="description" content="OnPoint Companies transforms distressed Boston properties into luxury housing through integrated development and construction management. Capturing the $75M+ New England development market." />
</svelte:head>

<div class="font-sans antialiased text-gray-900 bg-white">
  <TopBanner />
  <Navbar />
  <main>
    <Hero />
    <Intro />
    <Carousel />
    <ValueProp />
    <ShowroomGrid />
    <Steps />
    <Features />
    <Illustration />
    <Sustainability />
  </main>
  <Footer />
</div>

