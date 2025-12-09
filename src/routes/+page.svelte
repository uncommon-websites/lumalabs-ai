<script lang="ts">
	import "../app.css";
    import Header from "$lib/components/Header.svelte";
    import Hero from "$lib/components/Hero.svelte";
    import Mission from "$lib/components/Mission.svelte";
    import Products from "$lib/components/Products.svelte";
    import News from "$lib/components/News.svelte";
    import Research from "$lib/components/Research.svelte";
    import Community from "$lib/components/Community.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<Header />
<main>
    <Hero />
    <Mission />
    <Products />
    <News />
    <Research />
    <Community />
</main>
<Footer />

