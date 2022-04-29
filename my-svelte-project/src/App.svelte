<script  src="https://unpkg.com/aos@next/dist/aos.js">
	export let name;
	import Header from "./components/organisms/Header.svelte";
	import Footer from "./components/organisms/Footer.svelte";
	import Cloud from "./components/organisms/Cloud.svelte";
	import DomainSection from "./components/organisms/DomainSection.svelte";
	import Plans from "./components/organisms/Plans.svelte";
</script>
<Header/>
<main>	
	<Cloud/>
	<DomainSection/>
	<Plans/>
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

