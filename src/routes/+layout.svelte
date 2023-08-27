<script>
	import '../app.css';
	import Header from '../components/Header.svelte';
</script>

<div class="app">
	<main>
		<Header/>
		<slot />
	</main>
</div>
