<script>
    import Header from './Header.svelte';
    import Configure from './Configure.svelte';
    import LinkListWithHeading from './LinkListWithHeading.svelte';
    import Tip from './Tip.svelte';
</script>

<div class="sbdocs-wrapper">
	<Header />
	<Configure />
	<LinkListWithHeading />
	<Tip />
</div>

<style>
.sbdocs-wrapper{
	max-width: 1000px;
	width: 100%;
	margin: 0 auto;
	padding: 4rem 20px;
	box-sizing: border-box;
}
</style>
