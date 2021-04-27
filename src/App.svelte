<script>
	import Album from'./Album.svelte'
	let title = "Dogs"
	// export let name
	// const makananFavorit = ['Nasi Goreng','Indomi','Sup buntut']
</script>

<main>
<!-- 	{#if name !== ""}
		<h1>Hello {name}!</h1>
	{:else}
	<h1>Hello World!!</h1>
	{/if}

		{#each makananFavorit as fav}
			{#if fav === 'Indomi'}
				<li>{fav} Enak</li>
			{:else}
				<li>{fav}</li>
			{/if}

		{/each} -->
		<Album {title} />
	
</main>

<style>
	main {
		text-align: center;
		padding: 1em; /*em = ukuran font default = 16 px*/
		margin: 0 auto;
		background: rgb(240, 240, 240);
		height: 100vh;/*vh = viewport height*/
	}

/*	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}*/
</style>