<script>
	import celin_diagram from '$lib/images/celin.gif';
</script>

<svelte:head>
	<title>Celin Home</title>
	<meta name="description" content="Celin Home Page" />
</svelte:head>

<section>
	<img alt="Celin Diagram" src={celin_diagram} />
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	img {
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
