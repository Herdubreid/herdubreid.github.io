<script>
	import { page } from "$app/stores";
</script>

<header>
	<nav>
		<ul>
			<li>
				<a
					href="https://appsource.microsoft.com/en-us/product/office/WA200004096?tab=Overview"
					target="_blank"
					rel="noreferrer">AppSource</a
				>
			</li>
			<li>
				<a
					href="https://www.nuget.org/packages?q=celin.ais&prerel=true&sortby=relevance"
					target="_blank"
					rel="noreferrer">Nuget</a
				>
			</li>
			<li>
				<a
					href="https://www.powershellgallery.com/packages?q=celin."
					target="_blank"
					rel="noreferrer"
					>PS Gallery</a
				>
			</li>
		</ul>
	</nav>
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
	}

	nav {
		display: flex;
		width: 100%;
		justify-content: center;
		--background: rgba(255, 255, 255, 0.7);
	}

	ul {
		position: relative;
		padding: 0;
		margin: 0;
		height: 3em;
		display: flex;
		justify-content: center;
		align-items: center;
		list-style: none;
		background: var(--background);
		background-size: contain;
	}

	li {
		position: relative;
		height: 100%;
	}

	nav a {
		display: flex;
		height: 100%;
		align-items: center;
		padding: 0 0.5rem;
		color: var(--color-text);
		font-weight: 700;
		font-size: 0.8rem;
		text-transform: uppercase;
		letter-spacing: 0.1em;
		text-decoration: none;
		transition: color 0.2s linear;
	}

	a:hover {
		color: var(--color-theme-1);
	}
</style>
