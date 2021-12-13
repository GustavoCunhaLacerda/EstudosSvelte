<script>
	import Nav from "../components/layout/Nav.svelte";
</script>

<Nav />
<main class="content">
	<slot />
</main>
	

<style>
	main {
		margin-left: 300px;
	}
</style>
