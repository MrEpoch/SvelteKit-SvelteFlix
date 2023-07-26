<script>
    import Header from "./header.svelte";
    import Footer from "./footer.svelte";
    import "../style.css";
</script>

<sectiom class="page">
    <Header />
    <slot />
    <Footer />
</sectiom>

<style>
    .page {
        display: grid;
        min-height: 100vh;
    }
</style>
