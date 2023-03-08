<script>
    import Contact from "../lib/contact.svelte";
    import Footer from "../lib/footer.svelte";
    import Nav from "../lib/nav.svelte";
    export const prerender = true;
</script>

<main>
    <Contact />
    <div class="sticky">
        <Nav />
    </div>
    <slot />

    <Footer />
</main>

<style>
    .sticky {
        position: sticky !important;
        top: 0px;
        z-index: 4;
        background-color: white;
        box-shadow: rgba(0, 0, 0, 0.15) 1.95px 1.95px 2.6px;
    }
</style>
