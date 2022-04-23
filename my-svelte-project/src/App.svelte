<script  src="https://unpkg.com/aos@next/dist/aos.js">
	export let name;
	import Header from "./components/organisms/Header.svelte";
	import Footer from "./components/organisms/Footer.svelte";
</script>
<Header/>
<main>	
	<h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>
<Footer/>

<style>
	body {
		background-color: gold;
	}
	
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}
	

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>

