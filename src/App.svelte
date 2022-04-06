<script>
    import Header from './App/Header.svelte';
    import Configure from './App/Configure.svelte';
    import Learn from './App/Learn.svelte';
    import Tip from './App/Tip.svelte';
</script>

<div class="sbdocs-wrapper">
	<Header />
	<Configure />
	<Learn />
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
